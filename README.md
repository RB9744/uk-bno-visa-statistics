# UK BN(O) visa statistics, 2021 to 2026

Clean CSV files with the Hong Kong British National (Overseas) visa numbers published by the UK Home Office: applications, visas granted outside the UK, grants inside the UK, arrivals, and settlement (ILR) grants on the BN(O) route. Yearly and quarterly, from the start of the route on 31 January 2021 to the end of June 2026.

Maintained by the ILR Check team. Live version with charts and notes: https://ilrcheck.co.uk/bno-visa-statistics/

## Files

| File | What is in it |
|---|---|
| `bno_visas_yearly.csv` | One row per calendar year, 2021 to 2026 (2026 = January to June only) |
| `bno_visas_quarterly.csv` | One row per quarter, 2021 Q1 to 2026 Q2, including ILR grants |

## Columns

- `applications_outside_uk` : BN(O) visa applications made from outside the UK (entry clearance)
- `visas_granted_outside_uk` : BN(O) visas granted to people applying from outside the UK
- `grants_inside_uk` : BN(O) grants to people who applied from inside the UK (extensions and switching)
- `arrivals_rounded` : arrivals in the UK on a BN(O) visa, rounded by the Home Office to the nearest 100 (yearly file only)
- `ilr_grants_bno_route` : settlement (indefinite leave to remain) grants on the BN(O) route (quarterly file only)

Numbers are plain integers, no thousands separators.

## Totals in the data

- Applications from outside the UK: 194,249
- Visas granted outside the UK: 187,552
- Grants inside the UK: 54,284
- Arrivals: about 174,200
- Settlement grants on the BN(O) route: 39,629 (1,620 up to the end of 2025, then 8,184 in 2026 Q1 and 29,825 in 2026 Q2, when the first five-year cohort became eligible)

## Source

Home Office, Immigration System Statistics, year ending June 2026, published 27 August 2026. Tables used: Vis_D01 and Vis_D02 (entry clearance visas), Exe_D01 (extensions), Se_D02 (settlement). The arrivals figures come from the Home Office summary on safe and legal routes.

- Data tables: https://www.gov.uk/government/statistical-data-sets/immigration-system-statistics-data-tables
- Settlement summary: https://www.gov.uk/government/statistics/immigration-system-statistics-year-ending-june-2026/how-many-indefinite-leave-settlement-and-euss-settled-status-grants-have-been-issued-in-the-uk
- Safe and legal routes summary: https://www.gov.uk/government/statistics/immigration-system-statistics-year-ending-june-2026/how-many-people-come-to-the-uk-via-safe-and-legal-humanitarian-routes

The next Home Office release (year ending September 2026) is due on 26 November 2026. This dataset will be updated after each quarterly release.

## Licence

The underlying figures are Crown copyright, published under the Open Government Licence v3.0. This compilation is released under CC BY 4.0. If you use it, please credit "ILR Check" with a link to https://ilrcheck.co.uk/bno-visa-statistics/

## Related

- When BN(O) visa holders can apply for settlement, with a date tool: https://ilrcheck.co.uk/bno-ilr/
- ILR application fee: https://ilrcheck.co.uk/ilr-fee/
