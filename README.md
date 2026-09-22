# EV Adoption Across Indian States — Power BI Dashboard

## Overview
This project analyzes electric vehicle (EV) adoption across 35 Indian states and 
union territories, using official government registration data (Vahan, via Rajya 
Sabha replies) alongside EV policy data from CEEW and income data from the Ministry 
of Statistics and Programme Implementation (MoSPI).

Instead of just tracking total EV sales, the project investigates why adoption 
varies so widely — e.g. Delhi reaches 7.72% EV penetration while many larger 
states remain under 2% — by testing three possible barriers: state purchase 
incentives, public charging infrastructure, and per-capita income.

## Key findings
- National EV penetration: 3.38% (3.64M EVs of 107.53M vehicles sold, FY2019-20–FY2023-24)
- States with a two-wheeler purchase incentive average 4.07% EV share, vs. 2.33% 
  for states without one — the strongest of the three barriers tested
- Charging station density and income show weak or no relationship with adoption
- No single barrier explains low adoption everywhere — 5 states (West Bengal, 
  Jharkhand, Punjab, Madhya Pradesh, Jammu & Kashmir) face all three barriers, 
  while Tamil Nadu faces none of them despite below-average adoption

## Dashboard pages
1. **Overview** — national KPIs and EV share ranked by state
2. **Adoption Overview** — EV share ranked across all 35 states/UTs
3. **Barriers: Incentives** — EV share vs. months of active purchase incentive
4. **Barriers: Chargers** — EV share vs. public chargers per lakh vehicles sold
5. **Barriers: Income** — EV share vs. per-capita state income
6. **Barrier Profile** — which of the three barriers apply to each below-average state

## Data sources
- EV & total vehicle registrations: Rajya Sabha Unstarred Question replies (data.gov.in)
- Public/highway charging stations: Rajya Sabha Unstarred Question replies (data.gov.in)
- State EV policy incentives: CEEW-CEF, "A Comparison of EV Policies across Indian 
  States" (March 2023)
- Per-capita Net State Domestic Product: MoSPI Handbook of Statistics

## Tools
Power BI Desktop (Power Query, DAX measures, data modeling)

## Limitations
- Registration data is a 5-year cumulative total (FY2019-20 to FY2023-24), not a 
  current snapshot — Delhi's 7.72% reflects this whole period
- Telangana is absent from the EV registration source data
- CEEW policy data reflects incentives as of March 2023 and may not capture later changes
- "Low chargers" and "low income" are defined as below the median state — a simplification
- Correlational analysis on ~30 states; findings indicate association, not proof of causation
## Author
Omika Tiwari — [LinkedIn](https://www.linkedin.com/in/omika-tiwari) — [GitHub](https://github.com/Akimo404)



