# Options Tape Project — STATE FILE (read this first, every session)

## ⭐ DRAFTING PHASE — KICKOFF (2026-08-01; read this section in full before writing a word)

**Phase:** Data collection complete (10 runs, 8 trading closes, 07-22 → 07-31,
zero skipped). Edition drafting begins. Daily tape runs CONTINUE during
drafting ("run the tape"; snapshot agent is automatic at 08:11 IST).

**Edition type:** WORKFLOW edition (the flagship format). Load, per CLAUDE.md
and the workflow rules: `WORKFLOW_EDITION_FRAMEWORK.md`, `DEEP_DIVE_FRAMEWORK.md`,
`COMPLIANCE_FRAMEWORK.md` (wins all conflicts), `CURRENT_STATUS.md`, `voice.md`
(Mature register), `NEWSLETTER_CATALOG.md` (his published corpus — STUDY IT for
how he actually writes; this options subject is new territory, his corpus is
fundamental-research AI workflows, and the edition must feel native to that
brand, not like a flow-trading newsletter).

**Project files that carry the material:** this file top to bottom;
`process/methodology.md` (signal design, limitations); `data/scan-log.md`
(the full honest ledger); all 8 reports in `outputs/` (dated evidence);
`skill/SKILL.md` (what the tool actually does); snapshots in `data/snapshots/`
(the primary source every figure must trace to).

**Drafting protocol (Shubham's standing law, stated again 2026-08-01):**
1. OUTLINE FIRST — propose it, discuss, lock it with him. A locked outline is
   NOT permission to batch-draft.
2. Then ONE SECTION AT A TIME: intro first → discuss → his OK → next section.
   Never draft ahead.
3. INTERVIEW HIM for the personal beats: why he built an options tool as a
   decade-holder, his actual history/beliefs about options, what surprised
   him. Ask questions BEFORE writing story-bearing sections. Never invent a
   story (Compliance Rule 5); confess the belief, never reference private
   drafts/process artifacts in copy.
4. Visuals: where a chart/screenshot earns its place, BUILD the real file
   (dataviz skill for charts; real terminal/report screenshots from the repo),
   visually verify, never leave placeholders. One visual concept per need.
5. Every figure traces to a snapshot file, EDGAR accession, PTR DocID, or the
   scan log — re-verify against the file before a section locks; per-figure
   sources table accompanies the handover (visible-verification law).
6. Voice pass (voice.md, Mature register: no em dashes, zero exclamation
   marks, no contractions) → then `the-humanizer` skill as a review layer
   (its Local Overrides 7-10, added 2026-08-01, cover editions; voice.md wins
   any conflict) → Shubham human-finishes (Substack AI-scan reality).
7. GOAL: convert paid subscribers. A value-read even for a cold random
   reader — cold-reader law applies (no internal shorthand; "the tape,"
   "disagreement report" etc. get introduced in-copy before use).
8. Compliance pre-publish checklist runs in full at the end; vocabulary law
   throughout (never "plays"/"conviction score"/ranked buy lists; no
   buy/sell/hold framing anywhere; workflow-edition disclaimer variant).

**The story inventory (all evidence dated, in outputs/):**
- The reframe: a decade-holder builds an options screener NOT to trade —
  "is the options market disagreeing with me about a business I own?"
- Free primary data only (CBOE delayed JSON, EDGAR Form 4, House PTR PDFs) —
  vs. the paid-feed norm; the volume→OI overnight adjudication as free data's
  one clean trick, validated day 2.
- **5 kills** incl. the crown jewel: TSM Sep 450C, $17.9M, everything a flow
  alert would headline — OI unchanged next day; same-day round-trip; stock
  -4.5% the following session. A tool that cannot kill its own candidates is
  a tout sheet.
- **4 paid flags** (with event-window honesty MANDATORY in the telling):
  MSFT's week-long call block before +15.5%; AAPL's put wall before -7.4%;
  ACN's Oct 170P converting the day before -5.7%; SOLS's 55C before the
  beat-and-raise +5.4%. The tool flagged SIZE daily and refused direction
  claims inside event windows — post-hoc prescience is not claimed, ever.
- **1 resolved loss, recorded first:** ORCL's cleanest streak signal (115P,
  4 straight building sessions to 13,416) expired worthless. The ledger
  logs losses with the same prominence as wins.
- **1 live tension:** GOOGL's Sept put ladder — the book's highest formal
  score (4) while the stock rallied 12% against it. The backtest resolves,
  not the narrative.
- **4 build fixes kept visible** ("every wrong turn left in"): UTC date bug,
  DEEP_ITM mechanics flag (born from a 5-name flood of fake $100M put
  "signals"), weekend-OI timing discovery, per-ticker stale-cache handling.
- The ORCL barbell as the craft example: LEAPS crash floor + near-dated
  bounce calls + harvested puts, read from free EOD data.
- ACN sequence for humility: the cinematic 22k structure the tool refused to
  call bullish → killed → stock +25% in four days anyway, on fundamentals
  the tape never contained.

**Open decisions for Shubham at kickoff:** edition title + number; the tool's
public name ("the disagreement detector" is the working concept); which of
the 4 paid flags lead vs. support; how much SOLS/model-book adjacency is
allowed in copy (model book = paid-only rules still apply); the 7/23 teaser
Note (drafted, still unposted inventory per POSTING_LEDGER) — post before or
with the edition?; repo-public question (calendar-tell precedent has a public
repo pattern — does this one get one?).

---

**Last updated:** 2026-07-31 (Session 8 — Thursday-close run, Fri IST)
**Resolution day.** MSFT +15.5% on a verified beat (rev $90.0B, Azure +43%,
>$100B annualized) — the week-long call block the tool logged paid; the
edition framing is locked: flagged the size daily, refused the signal claim
inside the event window, said "unknowable," it paid anyway — both halves
stay. ORCL +8.3% → the 4-day 115P streak block (13,416) expires worthless
tonight = **backtest resolution #1: the streak signal LOST.** ACN Oct 170P
converted AND went ITM next day (-5.7%) = first full flag→conversion→payoff
cycle on a Tier-1 name. TSM dead-print zeros re-verified (+7.6% bounce =
irony logged). SOLS beat and RAISED (verified; belongs in the portfolio
watch too); its ATM 55C scores against Friday's reaction. COST Dec-28 LEAPS
~half stood. MCO feed recovered. Week 2 closes with Saturday's run
(AAPL+SOLS reactions, ORCL final entry, GOOGL post-window rescore).
**Outline: all material now in hand — 5 kills, 2 paid flags, 1 resolved
loss, the TSM round-trip lesson, 4 build fixes. Start on Shubham's go.**
---
*(prior status below)*
**Kill list doubled to 5:** TSM Sep 450C $17.88M and 530C $3.25M both DEAD
(OI unchanged — the project's biggest print was a same-day round-trip, and
TSM fell -4.5% the next session); ASML 1575P dead. The TSM kill is the
edition's crown-jewel honesty story: a print every flow service would have
headlined produced zero standing position. Converted: SOLS 55C (1,249, ATM,
earnings TONIGHT 7/30), ORCL 115P 4th straight rise to 13,416 — EXPIRES
Friday = the backtest's first fully-resolved position. New: ACN Oct 170P
$3.38M after +24.8%/4 sessions (hedge-shaped, watch 3); COST Dec-2028
1220C/1420C LEAPS $6.2M (watch 3-4). TSM standing flow flipped
bearish-protective. GOOGL ladder stall confirmed (fade marker holds).
Friday AM run = biggest adjudication day: MSFT reaction, AAPL+SOLS
reactions, ORCL expiry resolution, 4 conversion tests. Outline still
awaiting Shubham's go.
---
*(prior status below)*
**Day 5:** TSM printed the project's biggest bullish position (Sep 450C
$17.88M, 5.2x OI, no event window) — score 4 alongside ORCL (115P streak
now established; barbell intact). ACN +18.7% over three sessions (verified:
buybacks/dividend/AI+NATO + sector beta) right after the killed structure —
edition centerpiece: the tool refused to claim a signal it did not have, and
the rally happened anyway. SOLS: earnings THURSDAY 7/30 (verified — also
relevant to the portfolio watch); its Aug 55C buy-into-weakness is
event-capped at 2. GOOGL Sept ladder stalled = disagreement fading, honest
backtest marker set. MCO feed stale 3 runs — excluded. Next: Thu AM run
(MSFT+Fed reaction), Fri AM run (AAPL+SOLS reactions). **Edition outline
OVERDUE — start next session unless Shubham says otherwise.**
---
*(prior status below)*
**Adjudication day:** ACN 22k structure KILLED (zero conversion — the
flagship kill for the edition); ORCL 118P killed; ORCL 110P/Dec-27 100P,
AAPL Sep 330P, TSM Sep-27 280P, SOLS 80C all CONFIRMED standing. ORCL read
matured into a barbell (LEAPS crash protection growing INTO the bounce,
near-dated calls on, 124P harvested). Event windows this week: MSFT 7/29
AMC + Fed 7/29, AAPL 7/30, V 7/28 AMC, SPGI 7/28 (all verified via IR/press).
Five trading days of data complete (snapshots 07-22→07-27). **EDITION
OUTLINE IS NOW DUE** — material: two kills, validated adjudication loop,
three build fixes (UTC date bug, DEEP_ITM flag, weekend-OI timing), the ORCL
barbell, the ACN kill story. Next runs: Thu AM IST (MSFT+Fed reaction),
Fri AM IST (AAPL reaction).
---
*(prior status below)*
**Newest learnings:** (1) Weekend fetches carry Friday volume with THURSDAY's
OI — post-Friday OI posts US Monday pre-market, so the Monday run should be
~5:30 PM IST (one-off timing; normal cadence otherwise). (2) Per-ticker cache
staleness exists (MCO served Thursday's chain on Saturday — gap logged, not
hidden). (3) The week's story arc for the edition is strong: ACN's ~$300M
paired structure Thursday → +5.95% Friday (direction unknowable from EOD —
honest tension), and ORCL flagged Wed/Thu BEFORE Friday's S&P downgrade to
BBB- (early flags = tool working; Friday's put flood = reactive, and the
report says so). First SOLS signal (Aug 80C thin-chain build, provisional).
Edition outline due ~Monday.
---
*(prior status below)*
**Status:** LIVE AND VALIDATED. The volume→OI adjudication mechanism proved
itself on day 2: ALL of day-1's flagged positions converted to standing OI
(see `outputs/2026-07-23-disagreement-report.md`, definitive version). Two
build fixes made during the run, both good edition material: (1) date bug —
CBOE api timestamp is UTC, snapshots now stamped by latest actual trade time;
(2) DEEP_ITM auto-flag added after a 5-name flood of synthetic-stock
mechanics. Current leaders: ORCL watch note (score 4, two-sided caps it),
GOOGL (score 3, first-disagreement-item candidate if Sept put builds streak),
ACN paired ~$300M collar-shaped structure awaiting Monday's conversion test.
Streak scoring arms with the third snapshot (07-24 close, run Saturday
morning IST). Then: edition outline ~Monday per the drafting plan.

This file is the cross-session memory for this build. Any Claude session touching
"the options screener article" or "the options tape project" must read this file
top to bottom before doing anything. Update it at the end of every working session.

---

## What this is (the locked angle)

A Claude Code workflow that reads the US options tape as a **thesis-surveillance
instrument for a long-term quality investor** — NOT a trade-idea generator.

The question it answers: **"Is the options market disagreeing with me about a
business I own or cover?"** Output is a **disagreement report** on names in the
coverage universe: unusual positioning, insider selling, persistent put
accumulation that contradicts the long-term thesis. It stress-tests what Shubham
already believes; it never produces a ranked list of things to trade.

Edition hook (agreed): *"I buy businesses I want to own in ten years. I don't
trade options. I built an options screener anyway — because the tape is one of
the few places someone who knows something you don't leaves a footprint, and I
want to know when that footprint lands on a stock I own."*

## Origin & attribution (hard constraint)

- Idea sparked by a raw/ clipping of a Dave Wang article
  (`raw/How to build an unusual options screener (using Claude Code).md`).
- **Standing decision: Dave Wang is NEVER credited, referenced, or linked.**
  Therefore ZERO borrowing is load-bearing: our filters, scoring, data sources,
  and purpose must all be independently built. The only shared DNA allowed is
  the generic category "options data + Claude Code."
- Do NOT echo his framing ("insiders lol", "plays", "conviction score",
  "golden sweep"), his thresholds, his Unusual Whales/X MCP stack, or his
  PANW/MU examples.

## Deliberate differences from the source article (our edge)

1. **Purpose:** thesis surveillance for holdings/coverage, not whole-market trade hunting.
2. **Data:** 100% free primary/public sources (verified below), no paid feed, no API keys.
3. **Honesty:** congressional disclosures lag up to 45 days — treated as slow
   corroboration, never framed as real-time. Scoring is a hypothesis to backtest,
   not a validated edge; every scan is logged from day one; no cherry-picked wins.
4. **No social sentiment layer.** Dropped entirely (noise + authenticity rule).

## Compliance constraints (from COMPLIANCE_FRAMEWORK.md — wins all conflicts)

- Frame as "public disclosure data as a positioning signal," NEVER "profit from
  insiders' non-public information."
- Vocabulary ban in all copy: "plays," "conviction score," ranked buy lists.
  Use "divergence score" / "disagreement report." Flagged names are presented as
  what the machine surfaced, never as what to do.
- US-listed names only (Wall 1). Zero Indian securities in the universe, ever.
- Every figure in the eventual edition verified to primary source; AI disclosure;
  standing disclaimer.

## Data sources — VERIFIED WORKING 2026-07-23

| Layer | Source | Endpoint | Notes |
|---|---|---|---|
| Options chain (volume, OI, bid/ask, IV, last trade, prev close) | CBOE delayed quotes, free, no key | `https://cdn.cboe.com/api/global/delayed_quotes/options/{TICKER}.json` | Full chain JSON, ~15-min delayed. Tested on AAPL. |
| Insider transactions (Form 4) | SEC EDGAR, free | Atom feed: `https://www.sec.gov/cgi-bin/browse-edgar?action=getcompany&type=4&output=atom&CIK={CIK}` (needs User-Agent header with name+email) | Filed within 2 business days. Tested on AAPL. |
| Congressional trades (House PTRs) | House Clerk, free | Index: `https://disclosures-clerk.house.gov/public_disc/financial-pdfs/2026FD.zip` → `2026FD.xml` (FilingType `P` = PTR, 312 in 2026 so far); PDFs at `https://disclosures-clerk.house.gov/public_disc/ptr-pdfs/2026/{DocID}.pdf` | PTRs are PDFs → Claude parses them (good "AI does the ugly part" material). Up to 45-day lag. Tested: index + PDF both download. |
| Senate trades | efdsearch.senate.gov | — | **403 to plain curl.** Needs browser automation (playwright/firecrawl). Deferred to v2; House-only for v1, stated honestly. |

Free-data design consequence (IMPORTANT, this shapes the whole screener):
no intraday trade tape → **cannot detect sweeps or ask-side execution.** Instead
the signals are end-of-day: Vol/OI ratio, premium proxy (volume × price × 100),
**multi-day OI persistence** (needs daily chain snapshots — the scan log IS the
dataset), and put/call skew vs. the name's own baseline. EOD-persistence signals
actually fit the long-term reframe better than intraday tape-chasing.

## Build plan

- [x] **Session 1 (2026-07-23):** angle locked, data feasibility verified, repo
      scaffolded, state file + memory written. Universe locked (16 names).
      **First daily snapshot captured:** `data/snapshots/2026-07-22.md` (~974KB;
      all 16 chains at 2026-07-22 close; filter documented in file header).
      Build notes: (a) fetch with **curl**, not python urllib — this Mac's
      python3 lacks SSL certs; (b) snapshot format = per-ticker fenced CSV in
      one md file per trading day (vault is md-only); (c) SOLS keeps ALL
      contracts, others filter volume>=25 OR OI>=100.
- [x] **Session 2 (2026-07-23):** skill built and installed as `options-tape`
      (`~/.claude/skills/options-tape/` — SKILL.md + 4 scripts: config,
      take_snapshot, scan, fetch_form4, fetch_ptrs; workspace at
      `~/.claude/skills/options-tape-workspace/`). All scripts tested against
      live data. Methodology documented (`process/methodology.md` — signals,
      exclusion ladder, scoring, limitations; all independently designed).
      First live run complete (intraday): report in `outputs/`, scan log
      started (`data/scan-log.md`, append-only). Findings: Tier 1 quiet except
      ORCL watch note (near-dated put cluster, score 2; Henley Form 4 was
      10b5-1 → discounted); GOOGL post-earnings put ladder + Kean PTR sales;
      TSM bullish Aug 465C; NVDA Oct 180C +88k OI oddity to investigate.
      Key learning encoded in methodology: the volume→OI conversion check —
      tomorrow's snapshot adjudicates today's candidates.
- [ ] **Session 3+:** daily "run the tape" (definitive run = after US close;
      intraday runs overwrite same-date snapshot). Work the next-run checklist
      at the end of each report. Accumulate >= 5-7 trading days of history so
      streak-based scoring activates, then assess what the tool actually
      surfaces before drafting.

## Daily ops (set up 2026-07-23)

- **Data capture is AUTOMATIC:** macOS launch agent
  `com.shubham.options-tape-snapshot` (plist in `~/Library/LaunchAgents/`)
  runs `take_snapshot.py` daily at 08:11 IST — US market closed then, so it
  captures the prior close; fires on next wake if the Mac was asleep. Log:
  `~/.claude/skills/options-tape-workspace/snapshot-agent.log`. Snapshots
  accumulate even on days nobody opens Claude.
- **Judgment layer is MANUAL by design:** Shubham says "run the tape" any time
  between ~07:00 and ~18:30 IST (before the US open at 19:00 IST) — pairs
  naturally with the morning "run the watch" ritual. The skill re-snapshots
  (idempotent), scans, cross-refs, writes the dated report + scan-log line.
- Missed a day of judgment? No data is lost (agent snapshotted); the next run
  scores across the accumulated history.
- Teaser content decision (2026-07-23): tease the BUILD, never the findings —
  no tickers, no flagged names, no result claims until the edition publishes.
  Notes (and optionally a one-line P.S. in a paid thread) only; LinkedIn and
  Reddit wait for publication per platform laws.
- [ ] **Then:** draft the WORKFLOW edition per WORKFLOW_EDITION_FRAMEWORK.md,
      one section at a time (never batch-draft), in output/<folder per
      framework>/, showing real dated runs only.

## Universe — LOCKED 2026-07-23 (16 names)

Shubham asked for 10-20 names and delegated composition. Two tiers:

- **Tier 1 — coverage + model book (the "disagree with ME" core):**
  ACN, SOLS, LULU, ORCL
- **Tier 2 — quality-compounder bench** (transparent criteria: wide moat,
  10-year-plus holdability, liquid US-listed options; honest edition framing =
  "my coverage plus the kind of businesses I'd want to own"):
  MSFT, GOOGL, AAPL, NVDA, V, MA, COST, ASML, TSM, MCO, SPGI, ISRG

CBOE chains verified live for SOLS (150 contracts — thin, which makes anomalies
MORE visible), ACN (1,672), LULU (1,496), ASML (6,070), TSM (2,646), MCO (436).
PFC/Reliance excluded (Indian — compliance zero). **PANW and MU are permanently
excluded:** they are the two names the source article featured; our runs must
share nothing with it.

## Open decisions (ask Shubham, don't assume)

1. Whether the screener also gets a whole-market discovery mode later (v2).
2. Tool/edition name ("disagreement detector" is the working concept name).

## Session log

- **2026-07-23 (S1):** Verdict + reframe agreed with Shubham. Free-data-first
  confirmed by him ("what we can pull for free will make the most sense").
  CBOE/EDGAR/House verified working; Senate 403. Repo scaffolded. Universe
  locked at 16 names (he asked for 10-20 and delegated composition; chains
  verified incl. SOLS). Next: Session 2 builds the skill and does the first
  live run + first daily snapshot (snapshots can't be backfilled — start ASAP).
