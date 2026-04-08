# LINX Market Research Engine — Project Instructions

> These instructions apply to ALL work in this repository.
> Read meta/DIGEST_STANDARD.md and meta/RESEARCH_STYLE_GUIDE.md before producing ANY output.

## What This Repo Is
Autonomous market intelligence for LINX (trust-based luxury travel referral network) and Stein Retzlaff's cross-venture intelligence needs (LINX, AXIOM, Stein Studios).

## Non-Negotiable Rules

### 1. ZERO HALLUCINATION
- Every factual claim must have a source (URL, publication name, or report title)
- If WebSearch returns no results: write "No recent data found"
- If drawing from training data: write "Based on prior knowledge — verify current status"
- NEVER invent URLs, statistics, dates, or names
- If you don't know, say "Unknown"

### 2. 5W1H ON EVERY SIGNAL
Every market signal must answer: WHO, WHAT, WHEN, WHERE, WHY, HOW
If any element is unknown, explicitly write "Unknown" for that element.

### 3. DIGEST FORMAT
All daily digests follow meta/DIGEST_STANDARD.md exactly. No shortcuts. 1,500-2,500 words. Quartz-style.

### 4. CROSS-VENTURE COVERAGE
Digests must cover:
- LINX (referral network, operators, competitors, GTM)
- AXIOM (superyacht economy, charter market)
- Stein Studios (media, production, expedition filmmaking)
- Notable business/wealth/adventure news relevant to Stein's goals

### 5. RESEARCH QUALITY
All output follows meta/RESEARCH_STYLE_GUIDE.md:
- Confidence levels on every claim (CONFIRMED / LIKELY / UNVERIFIED)
- ICP scoring with full dimension breakdowns
- Anti-sycophancy: never present data optimistically to make LINX look good
- Density over volume: every sentence earns its space

### 6. EXCELLENCE NOT MEDIOCRITY
We are building the #1 technology platform in the world for travel and experiences.
"Industry standard" research is unacceptable. 100X the standard. Lead with what's WRONG, what's MISSING, what would FAIL under scrutiny. Then acknowledge what works.

## Daily Research Cycle

When running the daily research cycle:
1. Pull latest from git
2. Run competitive intelligence (update battle cards)
3. Run operator scout (5-8 new profiles from queue)
4. Run market pulse (daily report with 5W1H)
5. Generate executive digest (DIGEST_STANDARD.md format)
6. Create Gmail draft to steinretzlaff@gmail.com
7. Commit and push everything

## Key Files

| File | Purpose |
|------|---------|
| meta/DIGEST_STANDARD.md | Authoritative digest format (follow exactly) |
| meta/RESEARCH_STYLE_GUIDE.md | Quality standards for all output |
| meta/scoring-frameworks.md | 0-100 scoring rubrics |
| SIGNALS.md | High-priority findings log |
| RESEARCH_STATUS.md | Engine state and run history |
| operator-intelligence/queue/OPERATOR_QUEUE.md | Operator research queue |
| operator-intelligence/OUTREACH_TRACKER.md | Research-to-sales pipeline |
| hoa-enrichment/HOA_QUEUE.md | HOA research queue |

## Improvement Protocol

After every session where the founder gives feedback on research quality:
1. Update RESEARCH_STYLE_GUIDE.md
2. Update DIGEST_STANDARD.md if digest-specific
3. Apply immediately to the next cycle
4. We get better every day. Yesterday's standard is today's floor.
