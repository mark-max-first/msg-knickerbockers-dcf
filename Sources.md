# Sources and Model Documentation

## Primary SEC filings

1. [Madison Square Garden Sports Corp. FY2026 Form 10-K](https://www.sec.gov/Archives/edgar/data/1636519/000162828026056812/msgs-20260630.htm)
   - FY2024-FY2026 consolidated revenue categories and income statement
   - Cash flow from operations and capital spending
   - FY2026 cash and debt
   - Playoff-related revenue and expense discussion
   - Knicks local and national media-rights context
2. [October 2026 Rangers Form 10 information statement](https://www.sec.gov/Archives/edgar/data/2132873/000119312526419170/d122415dex991.htm)
   - FY2024-FY2026 Rangers carve-out revenue categories and income statement
   - Rangers cash flow and capital spending
   - Rangers cash and debt
   - Post-spin capitalization, diluted shares, and additional Knicks borrowing
   - Knicks credit-facility borrowing cost

## Market inputs and cross-checks

- [U.S. Treasury](https://home.treasury.gov/) - 5.24% 10-year Treasury yield on October 9, 2026
- [Aswath Damodaran](https://pages.stern.nyu.edu/~adamodar/New_Home_Page/home.htm) - 4.14% implied U.S. equity risk premium dated September 1, 2026
- [Yahoo Finance - Manchester United](https://finance.yahoo.com/quote/MANU/) - peer beta and 4.83x EV/revenue cross-check
- [PortfolioLab - Atlanta Braves Holdings](https://portfolioslab.com/symbol/BATRA) - 3.51x EV/revenue cross-check
- [StockAnalysis - MSG Sports market capitalization](https://stockanalysis.com/stocks/msgs/market-cap/) - October 9, 2026 market context only

## Historical carve-out logic

All figures below are in millions of dollars.

| FY2026 item | MSG Sports | Rangers | Derived Knicks residual |
|---|---:|---:|---:|
| Event-related revenue | 536.5 | 146.1 | 390.4 |
| Media-rights revenue | 295.7 | 61.7 | 234.0 |
| Sponsorship, signage, and suites | 255.3 | 111.2 | 144.1 |
| League distributions and other | 66.2 | 18.2 | 48.0 |
| Total revenue | 1,153.8 | 337.3 | 816.6 |
| Direct operating expense | 833.7 | 262.6 | 571.1 |
| SG&A | 286.0 | 101.6 | 184.4 |
| D&A | 3.2 | 2.3 | 0.8 |
| Operating income | 28.9 | (30.5) | 59.3 |

The workbook preserves every reported MSG Sports and Rangers value separately before calculating the Knicks residual.

## FY2026 normalization

- Reported Knicks home playoff games: 9
- Disclosed consolidated playoff-related revenue increase: $66.893 million
- Disclosed consolidated playoff-related expense increase: $49.532 million
- Base playoff revenue per home game: $10.0 million
- Base playoff expense per home game: $5.0 million

The model removes the disclosed championship premiums and the base per-game playoff amounts to create normalized FY2026 regular-season event revenue and non-playoff direct-cost bases. Forecast playoff revenue and expense are then rebuilt from each case's game count.

## WACC build

| Input | Value | Treatment |
|---|---:|---|
| Risk-free rate | 5.24% | Source-date 10-year Treasury yield |
| Equity risk premium | 4.14% | Damodaran implied ERP |
| Selected beta | 1.00x | Peer-informed and adjusted for single-team, control, and spin risk |
| Cost of equity | 9.38% | Risk-free rate + beta x ERP |
| Pre-tax cost of debt | 4.99% | Disclosed Knicks credit-facility borrowing cost |
| Target debt weight | 5.0% | Capital-structure assumption |
| Cash tax rate | 25.0% | Forecast assumption |
| Base WACC | 9.10% | Formula-derived |

## Treatment notes

- The valued entity is MSG Knickerbockers Corp., not the Knicks franchise alone.
- The valuation date is October 9, 2026.
- FY2024-FY2026 are historical. FY2027-FY2031 are forecasts.
- Public sports-company multiples are used only as a reasonableness check.
- Rangers carve-out results include corporate allocations and may not represent true future standalone costs.
- The workbook's WACC and terminal-growth sensitivity is formula-based because native Excel two-variable data tables require their input cells to live on the same sheet. The result is transparent, auditable, and responsive to the shared forecast without adding a second hidden case selector.
- No investment recommendation, trading signal, private information, or unsupported franchise valuation claim is included.
