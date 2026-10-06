# LBO Calculator

An interactive leveraged buyout model that shows where private equity returns come from: EBITDA growth, margin expansion, multiple expansion and debt paydown.

## Inputs (v1)

| Group | Input | Default |
|---|---|---|
| Entry | LTM revenue | ₹250 cr |
| | EBITDA margin | 20% |
| | Entry multiple | 8.0x |
| | Debt | 4.0x EBITDA |
| | Interest rate | 10% |
| | Transaction fees | 2% of EV |
| Operations | Revenue growth | 8% p.a. |
| | Margin change | 0 bps p.a. |
| | D&A / Capex | 3% / 4% of revenue |
| | Working capital | 10% of revenue increase |
| | Tax rate | 25.17% |
| Exit | Hold period | 5 years |
| | Exit multiple | 8.0x |

## Outputs
- IRR and MOIC
- Equity value bridge (returns attribution)
- Debt schedule with cash sweep
- Entry vs exit multiple sensitivity grid

## Status
Day 1 of a one-week build. Engine in progress.
