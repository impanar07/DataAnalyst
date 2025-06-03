The dataset, `car_prices.csv`, includes detailed information about used car listings such as:

- `year`: Year of manufacture
- `make`, `model`, `trim`, `body`, `transmission`: Vehicle specifications
- `vin`: Vehicle Identification Number
- `state`: Location of sale
- `condition`: Numeric rating of car condition
- `odometer`: Mileage of the car
- `color`, `interior`: Exterior and interior colors
- `seller`: Seller name or dealership
- `mmr`: Market value estimate
- `sellingprice`: Actual transaction price
- `saledate`: Date of sale

- Data Cleaning Process

Steps performed in the notebook:
- Loaded the dataset using `pandas`
- Checked for and handled missing values
- Dropped duplicate records
- Standardized categorical text fields (lowercase, no whitespace issues)
- Converted date columns (e.g., `saledate`) to datetime format
- Verified and fixed data types for numerical and date fields

Superstore Data Visualization Dashboard

Overview

This Power BI dashboard provides an in-depth business analysis of a retail superstore dataset, focusing on uncovering sales trends, profitability drivers, shipping efficiency, and customer segmentation performance. The dashboard is designed to aid decision-makers in identifying high-performing areas and improvement opportunities across products, regions, and customer types.

File Details
Filename: `Data visulization.pbix`
Data Source: Superstore sales dataset (CSV format)
Tool Used: Power BI
 Created For: Business stakeholders, analysts, marketing and operations teams

Dashboard Components & Key Visuals
Profit by Sub-Category
- Displays which product lines are most and least profitable.
- Highlights *Copiers* and *Phones* as profit drivers.
- Flags *Tables* for financial loss—requiring business attention.

Sales by Year
- A line chart showing consistent year-over-year growth.
- Visual proof of increasing customer base and market strength.

Sales & Profit by Segment
- Bar chart comparing *Consumer*, *Corporate*, and *Home Office* segments.
- Consumer leads in both sales and profitability.

Sales Distribution by Ship Mode
- Pie chart illustrating preferred logistics methods.
- *Standard Class* dominates (~60% of sales), suggesting cost and speed balance.
- 
Discount vs. Sales by Segment (Scatter Plot)
- Bubble chart showing how discounts affect revenue across segments.
- Shows *Consumer* segment responds well to discounts; *Home Office* does n
