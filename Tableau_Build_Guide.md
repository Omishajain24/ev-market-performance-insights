# Tableau Build Guide

## Worksheets
1. **Total EV Records:** put `Vehicle_Count` on Text using SUM (for the demo dataset).
2. **EV Type Mix:** `EV_Type` to Color, `Vehicle_Count` to Angle; choose Pie.
3. **Records by Year:** `Registration_Year` to Columns, `Vehicle_Count` to Rows; choose Line.
4. **Top Manufacturers:** `Make` to Rows, `Vehicle_Count` to Columns; choose Bar and sort descending.
5. **Top Models:** `Model` to Rows, `Vehicle_Count` to Columns; sort descending.
6. **Average Electric Range:** `Make` to Rows, `Electric_Range_Miles` to Columns; change aggregation to Average.
7. **Records by City:** double-click `City` or use it on Rows with `Vehicle_Count` on Columns.
8. **Model Year Distribution:** `Model_Year` to Columns, `Vehicle_Count` to Rows.
9. **Average MSRP by Type:** `EV_Type` to Columns, `Base_MSRP_USD` to Rows; set to Average.
10. **Eligibility:** `CAFV_Eligibility` to Rows, `Vehicle_Count` to Columns.

## Dashboard 1: EV Market Overview
- Add KPI, type mix, year trend, top manufacturers and city views.
- Add filters for `Registration_Year`, `EV_Type`, `Make`, and `City`.
- Use each filter menu > Apply to Worksheets > All Using This Data Source.
- Keep titles clear and formatting consistent.

## Dashboard 2: Manufacturer Analysis
- Add Top Manufacturers, Top Models, Average Electric Range, Model Year Distribution and MSRP/eligibility if available.
- Add `Make` and `EV_Type` filters.

## Story
Create 5 story points: Market Overview, Geographic Comparison, Manufacturer Analysis, Vehicle Characteristics, Recommendations. Add a short caption to each.

## Quality/performance checks
- Verify data types and inspect nulls and duplicate IDs.
- Test every filter and reset state.
- Confirm labels and tooltips are readable.
- Save as Tableau Packaged Workbook (`.twbx`) and reopen it.
- Do not publish confidential data to Tableau Public.

## Official source for real data
https://data.wa.gov/Transportation/Electric-Vehicle-Population-Data/f6w7-q2d2
