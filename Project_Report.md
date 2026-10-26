# Electric Vehicle Market Performance & Insights
## Project Report

### Objective
Build an interactive data-analysis dashboard to explore EV records by registration year, vehicle type, manufacturer, model, electric range, and city.

### Included deliverables
- `index.html`: interactive dashboard that opens in a browser and supports year/type/manufacturer/city filters.
- `EV_Market_Demo_Data.csv`: practice dataset.
- `Tableau_Build_Guide.md`: steps to recreate the visualizations in Tableau.
- `README.txt`: instructions and data caveat.

### Dataset note
The included CSV contains synthetic demonstration records for practicing the project workflow. It is not official market data and should not be used to claim real-world EV market performance. For a real submission, download the official Washington State Electric Vehicle Population Data:
https://data.wa.gov/Transportation/Electric-Vehicle-Population-Data/f6w7-q2d2

Historical population source:
https://data.wa.gov/Transportation/Electric-Vehicle-Population-Size-History/d886-d5q2

### Dashboard pages/views
1. EV Market Overview: KPI cards, yearly records, type mix.
2. Manufacturer Analysis: top manufacturers and average range by make.
3. Geographic Comparison: records by city.
4. Filters: registration year, vehicle type, manufacturer, city.

### Tableau creation workflow
1. Connect Tableau to the CSV through Connect > Text File.
2. Verify field types and check missing/duplicate records.
3. Build worksheets for count, type split, year trend, manufacturers, range, and city.
4. Create a dashboard and drag worksheets into the layout.
5. Add filters and apply them to relevant worksheets.
6. Create a Story with market overview, geography, manufacturers, vehicle characteristics, and recommendations.
7. Save as `.twbx` and test by reopening it.

### Conclusion
The dashboard demonstrates how interactive visual analytics can help explore vehicle records and compare manufacturers, vehicle types, ranges and locations. Conclusions about actual market conditions must be drawn only after replacing the synthetic sample with a verified official dataset and documenting its limitations.
