# Cummins (CMI) FP&A Forecast and Variance Model

**Educational portfolio project. Not investment advice.**

A driver-based forecast of Cummins' Q3 2026 and full-year 2026 sales and EBITDA, built segment by segment from SEC filings and anchored to management's own segment guidance. The Q3 budget was locked on October 7, 2026, before Cummins reported, so the Variance tab can score it against the real results in early November and split any miss into volume, price and margin effects.

## Headline numbers (budget v1.1)

| | Q3 2026 | FY2026 | Cummins guidance | Analyst consensus |
| --- | --- | --- | --- | --- |
| Net sales | $9.48B (+14.0%) | $37.3B (+10.8%) | +10% to +13% | Q3 $9.84B; FY $37.6B |
| Adjusted EBITDA margin | 18.6% | 18.2% | 18.0% to 18.5% | About 19.5% implied for Q3 |
| EPS | $7.53 | n/a | n/a | Q3 $8.40 |

The gap between the budget's $7.53 EPS and consensus $8.40 is the main finding: working the analysts' number back up implies a Q3 margin near 19.5%, above the top of Cummins' own guidance range. If Cummins only meets guidance, the market could still read it as a miss.

## What's in this repo

| File | What it is |
| --- | --- |
| `Cummins_FPA_Forecast_Model.xlsx` | The model. Opens on a dashboard with a bear/base/bull/custom scenario picker. |
| `Cummins_FPA_Project_Brief.pdf` | What the forecast is, why it matters and how it was built. |
| `Cummins_2026_Key_Insights.pdf` | Five insights, the scenario results and the numbers to watch in the Q3 report. |

## Workbook tabs

- **Start Here**: tab guide, colour guide and plain-English glossary.
- **Dashboard**: KPI tiles, Q3 check-in, scenario picker, segment table and charts.
- **Inputs**: every growth and margin driver, each with a dated source; segment guidance; analyst consensus.
- **Forecast**: Q3 and Q4 2026 by segment, adjusted EPS bridge, and four checks (segment guidance, seasonality, consensus, accuracy band).
- **Variance**: enter Q3 actuals; the EBITDA gap splits into volume and margin effects, and Engine sales into units vs price.
- **Backtest**: the same forecasting method applied to Q3 and Q4 2025, with its errors.
- **Change Log**: every change from v1.0 (Oct 7) to v1.1 (Oct 8), with reasons.
- **Historicals**, **Scenario Calc**, **Chart Data**: sourced data and supporting calculations.

## Method

1. Collected ten quarters of segment sales (Q1 2024 to Q2 2026) and six quarters of EBITDA from Cummins' 8-K earnings releases; every quarter ties to reported totals.
2. Added back $657M of one-off Accelera charges to show underlying trends.
3. Anchored each segment's growth and margin to Cummins' August 4, 2026 segment guidance. Company totals are outputs, not targets.
4. Checked seasonality, Wall Street consensus and the method's backtested accuracy; built an EPS bridge that ties to Q2 2026 reported EPS.
5. Stress-tested v1.0 with independent critiques and backtests, which found seven problems; all are fixed in v1.1 and documented in the Change Log.
6. Locked the budget and built the variance bridge for scoring against actuals.

## Sources

- Cummins Q2 2026, Q4/FY2025 and Q3 2025 earnings releases (SEC 8-K, Exhibit 99)
- Cummins Q2 2026 earnings call transcript (segment guidance)
- Yahoo Finance analyst estimates, accessed October 8, 2026
- Transport Topics, September 2026 Class 8 truck orders

Built in Excel and Python by Saaransh Coelho, with Claude as a modeling and review assistant, October 2026.
