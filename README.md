
# House Price Analysis & Market Insights Dashboard | Power BI

A brief description of what this project does and who it's for

# House Price Analysis & Market Insights Dashboard | Power BI



## Problem Statement

This dashboard helps users understand housing market trends, property prices, and regional sales performance. It provides insights into purchase prices, offer prices, average price per square metre, and housing market performance across different regions and property types.

Through interactive visualizations and filters, users can analyze how property prices vary by region, house type, and sales type. The dashboard also helps identify the relationship between housing prices and market indicators such as inflation, interest rates, and yield.

The dashboard provides a comprehensive view of housing market performance, enabling users to explore pricing patterns, sales trends, and regional differences to support data-driven analysis.

## Steps Followed

- Step 1: Loaded the housing price dataset into Microsoft Power BI Desktop.

- Step 2: Opened Power Query Editor to inspect the dataset and perform data cleaning and transformation wherever required.

- Step 3: Reviewed column quality, distribution, and data profiling to understand the structure and characteristics of the dataset.

- Step 4: Prepared the dataset for analysis by checking data types and ensuring the required columns were suitable for calculations and visualizations.

- Step 5: Created DAX measures for analyzing purchase prices, offer prices, average prices per square metre, and sales performance.

- Step 6: Developed time intelligence measures to calculate Year-to-Date (YTD) sales and rolling 12-month sales.

- Step 7: Created Year-over-Year (YoY) calculations to compare median purchase prices across different years.

- Step 8: Designed an interactive report using multiple dashboard pages to analyze overall housing market performance, sales overview, and regional and local breakdowns.

- Step 9: Added slicers to enable interactive filtering and analysis based on Region, Area, and City.

- Step 10: Created visualizations to analyze house type by offer and purchase price, helping compare pricing patterns across property categories.

- Step 11: Added visualizations for average inflation, interest rate, and yield by house type to understand the relationship between market indicators and property categories.

- Step 12: Developed a Prices over SQM visualization to compare property prices and price per square metre across different house types.

- Step 13: Created a Sales Overview page containing the following visualizations:

  - Sales by Region
  - Key Influencers affecting Purchase Price
  - Offer Price per Square Metre by Sales Type
  - Average Price per Square Metre by Region
  - Year, Quarter, Month, and Day-based sales table
  - Year-to-Date sales analysis

- Step 14: Developed a Regional & Local Breakdown page with Region, Area, and City slicers to enable detailed geographical analysis.

- Step 15: Applied customized dashboard themes, formatting, colors, titles, and layouts to improve readability and visual presentation.

- Step 16: Organized the dashboard into three report pages:

  - House Market Overview
  - Sales Overview
  - Regional & Local Breakdown

## Snapshot of Dashboard (Power BI Desktop)

### 1. House Market Overview

![House Market Overview](<img width="1920" height="1007" alt="HousePriceSample 11_12_2026 6_54_58 PM" src="https://github.com/user-attachments/assets/b72adb41-1d82-47b9-b3ce-9cd7ceacfc18" />)

### 2. Sales Overview

![Sales Overview](<img width="1920" height="1007" alt="HousePriceSample 11_12_2026 6_20_31 PM" src="https://github.com/user-attachments/assets/0c61a414-311e-4d8b-bf99-1e34cfb92ac1">)

### 3. Regional & Local Breakdown

![Regional and Local Breakdown](<img width="1920" height="1007" alt="HousePriceSample 11_12_2026 6_20_40 PM" src="https://github.com/user-attachments/assets/30c8ac46-1f45-4e84-8d31-3d2b8c36cc65">)

## Insights

A multi-page interactive dashboard was developed using Power BI Desktop to analyze housing market performance, sales trends, and regional price variations.

Following analytical observations can be explored through the dashboard:

### [1] Sales Performance Analysis

- Analyze purchase price trends across different years.
- Track Year-to-Date sales performance.
- Compare sales activity across different time periods.
- Identify changes in housing market performance using historical sales data.

### [2] Regional Analysis

- Compare housing sales across different regions.
- Identify regions with higher and lower purchase prices.
- Analyze average price per square metre across regions.
- Explore housing market performance at regional, area, and city levels.

### [3] House Type Analysis

- Compare offer prices and purchase prices across different house types.
- Analyze average inflation, interest rate, and yield by house type.
- Identify differences in pricing patterns between apartments, townhouses, and villas.

### [4] Sales Type Analysis

- Compare offer price per square metre across regular sales, other sales, family sales, and auctions.
- Identify variations in property pricing across different sales categories.

### [5] Price per Square Metre Analysis

- Analyze property prices relative to their size.
- Compare price per square metre across house types.
- Identify differences in housing price patterns across property categories.

### [6] Key Influencers Analysis

- Used the Key Influencers visual to identify factors associated with changes in purchase price.
- Explored how selected housing characteristics influence purchase price.
- Analyzed the relationship between housing attributes and property pricing.

## Tools & Technologies Used

- Microsoft Power BI
- DAX
- Power Query
- Data Modeling
- Data Visualization
- Time Intelligence

## Key DAX Measures

- Median Purchase Price
- Year-over-Year Median Price Change
- Year-to-Date Sales
- Last 12 Months Sales
- Average Purchase Price
- Average Price per Square Metre

## Dashboard Features

- Interactive Region, Area, and City slicers.
- Multi-page dashboard navigation.
- Housing market overview.
- Sales performance analysis.
- Regional and local market breakdown.
- House type and sales type comparisons.
- Time intelligence analysis.
- Key Influencers visualization.
- Dynamic and interactive visualizations.

## Repository Structure

```text
House-Price-Analysis/
│
├── README.md
│
├── Dataset/
│   └── housing_price_sample.csv
│
├── Dashboard/
│   └── HousePriceSample.pbix
│
└── images/
    ├── house-market-overview.png
    ├── sales-overview.png
    └── regional-local-breakdown.png
```

## Getting Started

1. Clone this repository:

   ```bash
   git clone <your-repository-url>
   ```

2. Open the `.pbix` file using Microsoft Power BI Desktop.

3. Update the dataset path if required.

4. Refresh the data.

5. Explore the dashboard using interactive slicers and visualizations.

## Author

**Ayush Khali**

Aspiring Data Analyst | Python | SQL | Power BI | Excel | Tableau

[LinkedIn](http://www.linkedin.com/in/ayush)

---

⭐ If you find this project interesting, feel free to explore the repository!
