# MSG Knickerbockers Standalone DCF

This project values MSG Knickerbockers Corp. after the proposed Rangers spin-off. The modeled company contains the New York Knicks and Westchester Knicks.

The core question is:

> What is the standalone equity value of MSG Knickerbockers, and how do playoff performance, media rights, sponsorships, ticketing, and team costs affect that value?

## Valuation conclusion

The normalized base case produces:

- **Enterprise value:** $916.4 million
- **Equity value:** $838.7 million
- **Implied value per diluted share:** $34.64
- **Downside / base / upside:** $2.57 / $34.64 / $128.42 per share
- **Base WACC / terminal growth:** 9.1% / 2.5%

This is an educational corporate-finance analysis, not an investment recommendation. The wide scenario range is intentional. It shows how a single-team sports company concentrates value in postseason inventory, commercial demand, and media-rights economics.

## Files

- `MSG_Knickerbockers_DCF.xlsx` - seven-tab Excel valuation model with a centralized case selector, historical carve-out, five-year forecast, DCF, sensitivities, sources, and independent checks
- `MSG_Knickerbockers_Valuation_Memo.pdf` - one-page recruiter-facing valuation memo
- `Sources.md` - source documentation, model boundaries, and treatment notes
- `Resume_Bullets.md` - two verified resume bullets tied to completed deliverables

## Methodology

1. Start with audited FY2024-FY2026 MSG Sports consolidated results.
2. Subtract the Rangers carve-out reported in the October 2026 Form 10 information statement.
3. Preserve the resulting Knicks historical residual separately from forecast assumptions.
4. Normalize FY2026 so the championship run is not treated as recurring.
5. Forecast FY2027-FY2031 event revenue, media rights, sponsorships and suites, league distributions, direct team costs, SG&A, capital spending, and working capital.
6. Calculate unlevered free cash flow as EBIT x (1 - tax rate) + D&A - capital spending - change in net working capital.
7. Discount forecast cash flows and a Gordon Growth terminal value using a formula-derived WACC.
8. Bridge enterprise value to equity value using post-spin cash, debt, and diluted shares.

## Sports-business findings

1. **Playoff inventory is the clearest variable driver.** Four annual home playoff games contribute about $41 million of FY2027 event revenue in the base case. Holding other base assumptions constant, moving from zero to ten games increases modeled value from $24.10 to $50.45 per share.
2. **Premium commercial revenue compounds.** Base sponsorship, signage, and suite revenue grows 5.0% annually and reaches $184.0 million by FY2031.
3. **Media rights create both durability and reset risk.** The base case assumes 2.5% annual growth with no FY2030 renewal step. The downside applies a 10% reset.

## Verification

The workbook passed all modeled acceptance checks:

- MSG Sports revenue and EBIT reconcile to Knicks residual plus Rangers carve-out for FY2024-FY2026.
- Post-spin cash and debt bridges reconcile.
- Zero downside playoff games produce zero playoff revenue and expense.
- More playoff home games increase value.
- Higher WACC lowers value.
- Higher terminal growth increases value.
- Upside value exceeds base value, which exceeds downside value.
- Enterprise value equals the present value of forecast cash flow plus terminal value.
- Workbook formula-error scan found no `#REF!`, `#DIV/0!`, `#VALUE!`, `#NAME?`, or `#N/A` errors.
- Every worksheet and the one-page memo received a rendered visual review.

## Important limitations

- Rangers historical statements include allocated corporate costs that may not equal future standalone economics.
- Public-company multiples are a secondary reasonableness check, not the primary valuation method.
- Franchise estimates and media reports are not treated as audited facts.
- Roughly 80% of the base enterprise value comes from terminal value.
- Scenario outputs are valuation mechanics, not share-price targets or trading signals.

See [Sources.md](Sources.md) for direct links and treatment details.
