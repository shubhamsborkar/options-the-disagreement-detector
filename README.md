# Options Tape Repo — the disagreement detector build

A Claude Code workflow that reads US options positioning (free CBOE delayed
data), insider Form 4s (EDGAR), and House congressional PTRs as a
**thesis-surveillance instrument**: does the options market disagree with the
long-term thesis on names Shubham owns or covers?

**Start here every session: [[PROJECT_STATE]]** — it holds the locked angle,
the attribution constraint, verified data endpoints, the build plan, and open
decisions. Update it before ending any working session.

Folders (same convention as `calendar-tell-repo/`):
- `data/` — daily chain snapshots + scan logs (the backtest dataset builds here)
- `process/` — build notes, methodology
- `outputs/` — dated disagreement reports
- `skill/` — the skill definition (installed copy lives in `~/.claude/skills/`)

End goal: a WORKFLOW newsletter edition built on real, dated runs of this tool.
