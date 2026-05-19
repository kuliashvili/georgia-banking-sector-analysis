# Georgia Banking Sector — Loan Analysis Dashboard
<img width="2325" height="2027" alt="Georgian Loans" src="https://github.com/user-attachments/assets/582ae4bd-6a5c-4c64-886f-d1f191b63ec9" />


## Overview
Interactive Power BI dashboard analyzing bank loans across 
Georgian regions from 2015 to 2026, using official data from 
the National Bank of Georgia (NBG) (https://nbg.gov.ge/en/statistics/statistics-data)

## Data Source
- **Source:** National Bank of Georgia (nbg.gov.ge)
- **Dataset:** LREG — Bank Loans in National Currency by Regions
- **Unit:** Million GEL
- **Period:** November 2015 — March 2026

## Tools Used
- Power BI Desktop
- Power Query (data cleaning & transformation)
- Microsoft Excel

## Data Cleaning Steps
1. Removed header/footer junk rows
2. Unpivoted 126 date columns into long format
3. Set correct data types (Date, Decimal)
4. Filtered out Total and null rows
5. Renamed columns for clarity

## Key Insights
- Tbilisi dominates Georgian lending (~64% of total loans)
- Consistent upward trend from 2015–2026 across all regions
- 2026 data is partial (Jan–Mar only)

## How to Use
1. Download the .pbix file
2. Open with Power BI Desktop (free)
3. Use the date slicer to filter by time period
4. Click any region in the bar chart to cross-filter all visuals
