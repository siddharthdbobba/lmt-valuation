# Sources and Input Audit

Every hard input below is tagged `[VERIFY]` so the model owner can tie it back to the latest Lockheed Martin 10-K, 10-Q, market data, or analyst assumption before use.

## Lockheed Martin 10-K Inputs

| Input | Value used | Units | Source | Tag |
|---|---:|---|---|---|
| FY2025 revenue | 75,048 | $mm | Lockheed Martin FY2025 Form 10-K, consolidated net sales | [VERIFY] |
| FY2025 operating profit | 7,731 | $mm | Lockheed Martin FY2025 Form 10-K, consolidated operating profit | [VERIFY] |
| FY2025 D&A | 1,800 | $mm | Lockheed Martin FY2025 Form 10-K, cash flow statement depreciation and amortization, approximate | [VERIFY] |
| FY2025 capex | 1,850 | $mm | Lockheed Martin FY2025 Form 10-K, additions to property, plant, and equipment, approximate | [VERIFY] |
| Cash and equivalents | 3,100 | $mm | Lockheed Martin FY2025 Form 10-K, balance sheet cash and equivalents, approximate | [VERIFY] |
| Total debt | 20,000 | $mm | Lockheed Martin FY2025 Form 10-K, short-term plus long-term debt, approximate | [VERIFY] |
| Diluted shares | 232.5 | mm shares | Lockheed Martin FY2025 Form 10-K, diluted weighted-average shares, approximate | [VERIFY] |
| Aeronautics sales | 30,260 | $mm | Lockheed Martin FY2025 Form 10-K, segment sales, approximate | [VERIFY] |
| Missiles and Fire Control sales | 14,450 | $mm | Lockheed Martin FY2025 Form 10-K, segment sales, approximate | [VERIFY] |
| Rotary and Mission Systems sales | 17,310 | $mm | Lockheed Martin FY2025 Form 10-K, segment sales, approximate | [VERIFY] |
| Space sales | 13,030 | $mm | Lockheed Martin FY2025 Form 10-K, segment sales, approximate | [VERIFY] |

## Market and Valuation Inputs

| Input | Value used | Units | Source | Tag |
|---|---:|---|---|---|
| Current share price | 493.60 | $/share | Recent market price around June 2026 | [VERIFY] |
| Risk-free rate | 4.49% | % | Recent U.S. 10-year Treasury yield around June 2026 | [VERIFY] |
| Equity risk premium | 5.00% | % | Analyst assumption, common U.S. ERP range | [VERIFY] |
| Levered beta | 0.63 | x | Market data provider beta for LMT, approximate | [VERIFY] |
| Pre-tax cost of debt | 4.80% | % | Analyst assumption based on LMT credit profile and recent rates | [VERIFY] |
| Debt weight | 22.0% | % | Analyst target capital structure | [VERIFY] |
| 2026 revenue growth | 4.0% | % | Analyst forecast based on backlog and defense demand | [VERIFY] |
| 2027 revenue growth | 3.5% | % | Analyst forecast | [VERIFY] |
| 2028 revenue growth | 3.0% | % | Analyst forecast | [VERIFY] |
| 2029 revenue growth | 2.7% | % | Analyst forecast | [VERIFY] |
| 2030 revenue growth | 2.5% | % | Analyst forecast | [VERIFY] |
| 2026 EBIT margin | 10.4% | % | Analyst forecast tied to FY2025 margin | [VERIFY] |
| 2027 EBIT margin | 10.6% | % | Analyst forecast | [VERIFY] |
| 2028 EBIT margin | 10.7% | % | Analyst forecast | [VERIFY] |
| 2029 EBIT margin | 10.8% | % | Analyst forecast | [VERIFY] |
| 2030 EBIT margin | 10.8% | % | Analyst forecast | [VERIFY] |
| Cash tax rate | 17.0% | % | Analyst normalized cash tax rate based on recent LMT tax profile | [VERIFY] |
| D&A percent of revenue | 2.4% | % | Derived from FY2025 D&A divided by revenue | [VERIFY] |
| Capex percent of revenue | 2.5% | % | Derived from FY2025 capex divided by revenue | [VERIFY] |
| Net working capital percent of revenue | 5.0% | % | Analyst assumption based on balance sheet working capital intensity | [VERIFY] |
| Perpetuity growth | 2.25% | % | Analyst terminal growth assumption | [VERIFY] |
| Exit EV/EBITDA multiple | 12.0x | x | Peer trading range assumption | [VERIFY] |

## Comparable Company Inputs

| Peer | Inputs used | Source | Tag |
|---|---|---|---|
| RTX | Share price, diluted shares, net debt, revenue, EBITDA, net income | Recent market data and latest company filings, approximate | [VERIFY] |
| NOC | Share price, diluted shares, net debt, revenue, EBITDA, net income | Recent market data and latest company filings, approximate | [VERIFY] |
| GD | Share price, diluted shares, net debt, revenue, EBITDA, net income | Recent market data and latest company filings, approximate | [VERIFY] |
| LHX | Share price, diluted shares, net debt, revenue, EBITDA, net income | Recent market data and latest company filings, approximate | [VERIFY] |
| BA | Share price, diluted shares, net debt, revenue, EBITDA, net income | Recent market data and latest company filings, approximate | [VERIFY] |

## Notes

- The workbook is intentionally structured so the model owner can replace every blue-font input and have the valuation update through formulas.
- Historical LMT financials should be verified against the latest filed 10-K before this project is shown as a final valuation.
- Peer trading data changes daily and should be refreshed before use.
