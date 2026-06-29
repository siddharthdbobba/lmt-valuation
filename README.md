# LMT Valuation

This project is an investment-banking-style valuation model for Lockheed Martin Corporation (NYSE: LMT). It is built as a portfolio and interview prep artifact for walking through a DCF, comparable company analysis, valuation range, and key assumptions.

## Files

- `build_model.py`: Python generator that creates `LMT_Valuation.xlsx`.
- `LMT_Valuation.xlsx`: Formula-driven Excel model with Summary, Assumptions, DCF, Comps, and Sensitivity tabs.
- `MEMO.md`: One-page investment memo.
- `SOURCES.md`: Source and verification audit for hard inputs.

## Regenerate the Workbook

Run:

```bash
python3 build_model.py
```

The script uses `openpyxl` and writes `LMT_Valuation.xlsx` in this directory.

## Methodology

The model starts with FY2025 Lockheed Martin financials, then forecasts five years of revenue, EBIT, taxes, D&A, capex, net working capital, and unlevered free cash flow. The DCF uses both Gordon growth and exit EV/EBITDA terminal value methods, then bridges enterprise value to equity value and implied share price. The comps tab uses aerospace and defense peers to cross-check implied valuation through EV/Revenue, EV/EBITDA, and P/E.

## Limitations and Assumptions

This is a student valuation model, not investment advice. Inputs are approximate and are flagged in `SOURCES.md` with `[VERIFY]` because they should be refreshed against the latest 10-K, 10-Q, Treasury yield, beta, market price, and peer trading data before use. The main purpose is to demonstrate valuation structure, formula discipline, and interview-ready reasoning.
