# LINX Research Engine — Scoring Frameworks

> All research entities are scored 0-100 using standardized rubrics.
> These frameworks are embedded in each agent's prompt.

---

## 1. Operator ICP Fit Score (0-100)

Used by: Operator Scout agent

| Dimension | Max Points | Scoring |
|-----------|-----------|---------|
| Asset proximity (Tier 1-3) | 20 | Owner=20, Owner+managed=15, Curated=10, Multi-layer=5, Reseller=0 |
| Revenue band ($1M-$50M) | 15 | $5-25M=15, $25-50M=12, $1-5M=10, <$1M=5, >$100M=5 |
| Referral dependency | 20 | >80%=20, 50-80%=15, 30-50%=10, <30%=5 |
| Commission arbitrage | 15 | Pays >15% now=15, 10-15%=10, <10%=5 |
| Brand quality | 10 | Ultra-luxury=10, Luxury=8, Premium=5, Mass-premium=2 |
| Technology readiness | 10 | API/modern CRM=10, Modern website=7, Basic site=5, None=0 |
| Approachability | 10 | Stein direct=10, 1-degree=7, 2-degree=5, Cold=3 |

**Interpretation:**
- 80-100: Immediate outreach target (Wave 1)
- 60-79: Warm pipeline (Wave 2)
- 40-59: Targeted outreach (Wave 3)
- <40: Not ICP fit or future phase

---

## 2. Competitive Threat Score (0-100)

Used by: Competitive Intelligence agent

| Dimension | Max Points | Scoring |
|-----------|-----------|---------|
| Funding trajectory | 25 | Seed=5, A=10, B=15, C=20, D+=25, Public=25 |
| Feature parity with LINX | 25 | Attribution=10, Referral tracking=10, Trust scoring=5 |
| Market overlap | 20 | Luxury travel=10, Referral model=5, Peer-to-peer=5 |
| Customer momentum | 15 | Based on users/operators YoY growth rate |
| Product velocity | 15 | Releases per quarter, roadmap ambition |

**Interpretation:**
- 80-100: CRITICAL threat — monitor daily, prepare counter-strategy
- 60-79: HIGH threat — monitor weekly, track feature releases
- 40-59: MEDIUM threat — monitor monthly, note positioning shifts
- <40: LOW threat — quarterly check

---

## 3. HOA Travel Affinity Score (0-100)

Used by: HOA Enrichment agent

| Dimension | Max Points | Scoring |
|-----------|-----------|---------|
| Median home value | 20 | >$10M=20, $5-10M=15, $3-5M=10, $1-3M=5 |
| Marina/yacht access | 15 | On-site marina=15, Nearby=10, None=0 |
| Private aviation proximity | 10 | On-site helipad/strip=10, <30min to private terminal=7, None=0 |
| Adventure/travel culture | 15 | Known travel community=15, Some signals=10, Unknown=5 |
| Concierge services | 10 | Full concierge=10, Basic=5, None=0 |
| Notable UHNW residents | 10 | Public info: many=10, some=5, unknown=0 |
| Seasonal migration | 10 | Members travel to adventure destinations=10, some=5 |
| Operator proximity | 10 | Near charter/safari/expedition operators=10, some=5 |

**Interpretation:**
- 80-100: Prime LINX user acquisition target (Phase 0-1)
- 60-79: Strong potential (Phase 1-2)
- 40-59: Moderate potential (Phase 2+)
- <40: Not priority target

---

## 4. Market Signal Priority (CRITICAL / HIGH / MEDIUM / LOW)

Used by: All agents for SIGNALS.md

| Priority | Criteria | Response |
|----------|----------|----------|
| CRITICAL | Direct threat to LINX positioning, competitor enters our exact space, regulatory change blocking our model | Immediate flag, same-day action required |
| HIGH | Competitor funding/acquisition, major market shift, high-fit operator discovered (>80/100) | Flag in daily digest, action within 48 hours |
| MEDIUM | Industry trend, new competitor below threshold, pricing intelligence | Include in weekly synthesis |
| LOW | Background noise, distant market signal, low-fit operator | Archive for monthly review |

---

*All scoring frameworks are embedded in agent prompts. Updates to frameworks should be reflected in trigger configurations.*
