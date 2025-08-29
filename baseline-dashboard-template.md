# Baseline Analytics Dashboard Template (Days 1–7)

Purpose: Single source of weekly KPI truth; lightweight (Google Sheet / Notion). Capture BEFORE improvements (Week 0) and then weekly snapshots.

## 1. Metric Definitions & Formulas
| Metric | Definition | Formula (Sheet) | Notes / Target by Day 90 |
|--------|------------|-----------------|--------------------------|
| Sessions | Visits to Etsy listings/shop | Raw import (Etsy Shop Stats export) | +20% vs Baseline |
| Views | Total listing views | Raw | Track alongside Sessions (views/session) |
| CTR | Listing click-through from search impressions | =Clicks/Impressions | Improve via title, thumbnail, tags |
| Conversion Rate (CR) | Orders / Sessions | =Orders/Sessions | +1 pp lift target |
| Orders | Completed sales in period | Raw | Break out by bundle vs single after launch |
| Revenue | Gross sales (EUR) | Sum(Order Value) | Track net after fees separately once ready |
| AOV | Avg order value | =Revenue/Orders | +10–15% target |
| Repeat Purchase Rate | Returning customer orders / total orders | =Repeat Orders/Orders | 18% → 23–25% |
| Email List Size | Total active subscribers | Raw (ESP) | 0 → 500+ (initial) |
| Email Revenue Share | Email attributed rev / total rev | =Email Rev/Revenue | 0% → 6–8% |
| Review Velocity | New reviews / week | Count(new reviews) | Maintain/increase (quality) |
| Review Rate | Reviews / Orders | =New Reviews/Orders | Keep ≥15% |
| Favorites (Saves) | New listing favorites | Raw | Proxy for future demand |
| Add-to-Cart Rate | Adds / Sessions | =Adds/Sessions | Diagnostic for CRO |
| Refund / Return Rate | Refund orders / total orders | =Refunds/Orders | Keep <2% |
| Etsy Ad Spend | Paid media spend | Raw | Cap <12% of revenue early |
| Ad ROAS | Rev from ads / ad spend | =Ad Rev/Ad Spend | Scale winners >3x |
| UGC Asset Count | New customer photos/videos captured | Raw | Goal: 10+ new in 90 days |

## 2. Sheet Structure
Recommended Tabs:
1. Weekly_Snapshot (primary dashboard)
2. Raw_Export (paste Etsy stats export)
3. Calculations (helper formulas / pivot)
4. Keyword_Rank (tracking position for 10–15 core keywords)
5. Experiments_Log (A/B tests, bundles, price changes)

## 3. Weekly Snapshot Table (Populate)
| Week | Date Range | Sessions | Impr. | CTR | Orders | Conv Rate | Revenue (€) | AOV (€) | Repeat Orders | Repeat % | New Reviews | Review Rate | Email Subs | Email Rev (€) | Email % | Ads Spend (€) | Ads Rev (€) | ROAS | Notes (Events/Changes) |
|------|------------|----------|-------|-----|--------|-----------|-------------|---------|---------------|----------|-------------|-------------|------------|---------------|---------|---------------|-------------|------|-------------------------|
| 0 (Baseline) | DD MMM – DD MMM | | | | | | | | | | | | | | | | | | Baseline capture |
| 1 | | | | | | | | | | | | | | | | | | | |
| 2 | | | | | | | | | | | | | | | | | | | |
| 3 | | | | | | | | | | | | | | | | | | | |
| 4 | | | | | | | | | | | | | | | | | | | |

## 4. Keyword Ranking Tracker (Manual / Tool Assist)
Track top queries weekly (search results position or relative impressions share):
| Keyword Core | Variant/Long Tail | Baseline Position / Impr Rank | Week 1 | Week 2 | Week 3 | Week 4 | Notes / Action |
|--------------|------------------|-------------------------------|--------|--------|--------|--------|----------------|
| dragon scale gloves | dragon scale fingerless gloves | | | | | | Optimize hero images |
| fingerless gloves | warm fingerless gloves women | | | | | | Add typing use-case photo |
| crochet arm warmers | lace crochet arm warmers | | | | | | Strengthen tags |
| steampunk gloves | gothic arm warmers | | | | | | Add steampunk bundle |
| winter gift | winter gift for her handmade | | | | | | Gift messaging |
| sustainable knitwear | eco friendly gloves | | | | | | Materials callout |

## 5. Experiment Log
| ID | Start Date | Hypothesis | Change Implemented | Metric Targeted | Baseline Metric | Result After 2 Weeks | Status | Learnings |
|----|------------|------------|--------------------|-----------------|-----------------|----------------------|--------|----------|
| EXP-001 | | Improving thumbnail brightness for Dragon Scale Gloves will raise CTR 10% | Re-shot hero images (higher exposure) | CTR | x.xx% | | Pending | |
| EXP-002 | | Adding bundle (Gloves + Headband) lifts AOV | New bundle listing + cross-link | AOV | €xx.xx | | Pending | |

## 6. Data Capture Processes
- Daily (light): Orders, Reviews, Notable customer messages (qual insight)
- Weekly (Sun PM): Export Etsy shop stats (CSV) → Raw_Export; refresh snapshot formulas.
- Monthly: Deep keyword position check & competitor scan.

## 7. Implementation Notes
- Color code variances vs baseline (green ≥ +10%, amber 0–10%, red negative).
- Freeze Week 0 BEFORE launching listing edits; if edits already started, treat earliest full week pre-edits as Baseline.
- Consider using a Notion database for Experiment Log with relation to impacted listings.

## 8. Initial Data Gaps & Assumptions
- Email metrics will be blank Week 0 (pre-launch). Fill after platform selection.
- Keyword positions require manual or third-party snapshot (record methodology to stay consistent).

## 9. Quick Reference (Formulas Example)
- CTR: =IF(Impressions=0,"",Clicks/Impressions)
- Conv Rate: =IF(Sessions=0,"",Orders/Sessions)
- AOV: =IF(Orders=0,"",Revenue/Orders)
- Review Rate: =IF(Orders=0,"",NewReviews/Orders)
- Repeat %: =IF(Orders=0,"",RepeatOrders/Orders)
- Ad ROAS: =IF(AdSpend=0,"",AdRevenue/AdSpend)

## 10. Next Steps After Baseline
1. Populate Week 0.
2. Implement Top 10 high-impact listing fixes (from backlog) in Week 2 to isolate effects.
3. Launch first bundle + track AOV shift.
4. Begin collecting email signups (insert card / link-in-bio).

---
Prepared: Day 1–2 deliverable.
