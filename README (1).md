## **Project Objective:**
This project focuses on building an end-to-end interactive dashboard in Power BI to analyze and visualize car sales data. The objective is to track sales trends over time, compare performance across various dimensions, and enable users to interact with the data through dynamic visuals and filters.
## Data Files
- dataset.xlsx: Original Excel data used in Power BI
- dataset.csv: Converted version for quick preview on GitHub
-<a href="https://github.com/Thirisha255/Power-BI-Car-Sales-Dashboard/blob/main/Car%20sales%20dataset.xlsx">Dataset</a>
##  Data Preparation & Transformation:
- Performed data cleaning using Power Query, ensuring column consistency, correct data types, and removal of null or duplicate values.
- Assessed column quality and distribution to validate data integrity before modeling.
- Built a custom Calendar Table using DAX to account for non-sales days (e.g., weekends, holidays), enabling accurate data-based analysis.
##  Data Modeling:
**Applied a Star Schema model with:**
- Calendar table as the primary (dimension) table.
- Car Sales table as the fact table.
- Created one-to-many relationships between calendar and sales data for accurate aggregation and filtering.
- Enabled efficient slicing and time intelligence across multiple visuals.
##  Key KPIs & DAX Calculations:
**Developed dynamic KPIs using DAX time intelligence functions to calculate:**
- YTD, MTD, YOY, and PYTD for Total Sales, Cars Sold, and Average Price.
- Difference between YTD and PYTD, with conditional formatting:
- Green indication for positive growth.
- Red indication for negative values.
## Dashboard Visuals:
- YTD Sales Weekly Trend – Area chart with a dynamic max point label.
- Total Sales by Body Style – Donut chart.
- Total Sales by Color – Donut chart.
- Cars Sold by Dealer Region – Interactive map visual.
- Company-wise Sales Table – Grid showing Avg. Price, Cars Sold, Total Sales, and % of Total Sales.
##  Detailed Reporting & Interactivity:
- Created a Detail Page with a full transactional table view including:
- Car ID, Sale Date, Customer Name, Dealer, Company, Model, Color, and Total Sales.
**Added Slicers/Filters for:**
- Body Style, Dealer Name, Transmission, and Engine Type.
- Built page navigation buttons for easy toggling between Overview and Detailed pages.
##  Tools & Techniques Used:
- Power BI Desktop for report building
- Power Query for ETL process
- DAX for custom KPIs and calculations
- Star Schema data modeling
- Dynamic visuals and conditional formatting
- User-friendly UI with slicers and navigation buttons
##  Skills Demonstrated:
- Advanced DAX and Time Intelligence
- Data modeling using best practices
- Effective use of interactive visuals
- Business-centric storytelling through dashboards
- Performance analysis and insight generation
## Dashboard Image
-<a href="https://github.com/Thirisha255/Power-BI-Car-Sales-Dashboard/commit/2adccfa36b8b2cfa5aa8a5a6182244742d118dbc">Dashboard image</a>
## Outcome:
This project demonstrates my ability to handle the complete Power BI lifecycle—from data extraction and transformation to modeling, calculation, visualization, and dashboard publishing—while keeping business goals and user experience in focus.
