# Canadian Bank Analyzer — TD vs. RBC

Comparative financial analysis model for Canada's two largest banks, built in Excel using real data from TD and RBC's FY2024 40-F filings with the SEC.

Three years of financials. Ten ratios across four categories. One recommendation.

---

## Analytical Framework

Banks require a different analytical lens than most companies. The model is organized around four categories that bank analysts actually use:

**Profitability** — ROE, ROA, and net profit margin. For Canadian banks, ROE above 13% is considered strong. Below 10% raises questions about whether the business is earning its cost of capital.

**Efficiency** — The efficiency ratio (non-interest expenses divided by total revenue) is the most-watched cost metric in banking. Below 60% is the threshold. Above it, the bank is either overspending or underearning — either way, something needs explaining.

**Asset Quality** — Provision for Credit Losses as a percentage of total loans shows how much the bank is setting aside for expected defaults. The loans-to-deposits ratio shows whether the bank is lending aggressively or conservatively relative to its funding base.

**Capital Strength** — Equity-to-assets measures the leverage cushion. The dividend payout ratio tells you whether the dividend is backed by real earnings or being stretched thin.

---

## Data

TD and RBC both report on October 31 fiscal year-ends, so the comparison is clean — same period, same IFRS standard.

| Source | Filing |
|---|---|
| TD Bank Group | Form 40-F FY2024, SEC EDGAR, December 2024 |
| Royal Bank of Canada | Form 40-F FY2024, SEC EDGAR, December 2024 |

FY2022 through FY2024 are included so the model shows trends, not snapshots.

---

## Results

| Metric | TD FY2024 | RBC FY2024 | Winner |
|---|---|---|---|
| ROE | 8.2% | 13.8% | RBC |
| ROA | 0.43% | 0.73% | RBC |
| Net Profit Margin | 15.4% | 28.3% | RBC |
| Efficiency Ratio | 62.0% | 59.7% | RBC |
| PCL / Loans | 0.46% | 0.33% | RBC |
| Loans / Deposits | 74.8% | 76.8% | Tie |
| Equity / Assets | 5.59% | 5.27% | Tie |
| Payout Ratio | 84.1% | 48.7% | RBC |
| CF / Net Income | 1.88x | 1.36x | TD |

**Scorecard: RBC 7 — TD 1 — Ties 2**

**Recommendation: RBC Outperform | TD Hold**

---

## What Happened in FY2024

TD and RBC entered FY2024 with nearly identical revenue — $57.2B vs $57.3B. They ended it with a $7.4B net income gap.

TD was hit with a USD $3B fine from US regulators for anti-money laundering control failures, the largest such penalty ever imposed on a Canadian bank. Non-interest expenses jumped from $29.9B to $35.5B. Net income fell from $10.6B to $8.8B. The bank was placed under a US retail asset cap that limits its growth south of the border. Every profitability metric in this model reflects that.

RBC went the other direction. It closed the acquisition of HSBC Bank Canada in March 2024 — 800,000 clients, 100+ branches, $453M in net income added to its results. Revenue grew, margins held, efficiency stayed below 60%.

Both banks saw rising PCLs as Canadian borrowers renewed mortgages at higher rates. That's a sector headwind, not a company-specific problem. The divergence between the two banks in FY2024 is almost entirely explained by the AML fine on one side and the HSBC acquisition on the other.

---

## Workbook

Five sheets:

- **Raw Data** — Income statement, balance sheet, cash flow for both banks FY2022-2024, with source citations per row
- **Ratio Comparison** — 10 ratios side-by-side with industry benchmarks, winner flags, and analyst commentary
- **Scoring Dashboard** — Summary scorecard and final recommendation
- **Visual Comparison** — Clustered bar charts: ROE, Net Income, Efficiency Ratio across three years
- **Analyst Memo** — Written recommendation with key findings, risks, and data sources

---

## Built With

Excel (openpyxl), SEC EDGAR 40-F filings, IFRS financial statements, Canadian bank sector benchmarks.

---

*Built for educational purposes. Not investment advice.*
