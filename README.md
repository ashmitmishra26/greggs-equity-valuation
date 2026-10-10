https://docs.google.com/spreadsheets/d/1sB8icAHrZEwUKKWcVFRKEUthV16T8ssH/edit?usp=drive_link&ouid=111781008420291526131&rtpof=true&sd=true

# Greggs plc Equity Valuation

**[View the model in your browser (Google Sheets, view-only)](PASTE_DRIVE_LINK_HERE)** · or download `Greggs valuation.xlsx` above

Independent valuation of Greggs plc (LSE: GRG) as at 28 September 2026, built in Excel.

## Conclusion

| | |
|---|---|
| DCF value per share | **£14.35** |
| Share price (28/09/2026) | £18.48 |
| Implied downside | **22%** |
| WACC | 11.67% |

On base-case assumptions the shares trade above intrinsic value. The gap comes down mostly to the discount rate. The WACC sensitivity shows the current price is only justified at a WACC of around 9.7%, against my estimate of 11.67%.

## Method

**DCF (primary)**
- 5-year forecast (FY2026 to FY2030) built from H1 FY2026 interim results, with revenue split into H1 actuals and an H2 forecast
- Valued on a cash-rent basis: under IFRS 16, rent is treated as an operating cost, so lease liabilities are excluded from both the equity bridge and the WACC debt weight
- Terminal value uses the value-driver formula, with reinvestment set at g / RONIC (2% growth, 15% RONIC), not a plain perpetuity on final-year cash flow
- Stub-period adjustment: H2 FY2026 cash flow is split at the valuation date, so the pre-valuation portion goes into cash and only the remainder is discounted
- Equity bridge covers net cash, finance-lease receivables, associates, non-controlling interests and the interim dividend already declared

**Trading comparables (cross-check)**
- LTM EV/EBITDA, EV/revenue and P/E against UK listed food and leisure peers, on an IFRS 16-consistent basis

**Sensitivities**
- WACC on its own, and a WACC × terminal growth grid

## Key assumptions to challenge

1. **Beta (1.37).** This drives the 11.67% WACC, and the downside call depends heavily on it.
2. **FY2026 margin.** Assumes H2 profit growth slows sharply after a strong H1.
3. **Comparables.** The peer set is small and structurally different from Greggs (freehold-heavy pubs, franchised pizza), so the multiples are a sense check, not a second valuation.

## Files

- `Greggs valuation.xlsx`: full model, covering assumptions, forecast, WACC, DCF, sensitivities and comparables

## Sources

Greggs plc annual and interim reports, closing share prices and gilt yields as at 28 September 2026, and peer company filings.

*Independent project for learning purposes. Not investment advice.*
