# Superstore Sales & Profit Analysis

An interactive Excel Business Intelligence project analyzing sales, profit, customers, products, and shipping performance using the Sample Superstore dataset.

## Project Overview

The goal of this project is to explore Superstore's sales and profitability from 2014 to 2017, identify business trends, and present the findings in interactive Excel dashboards.

The project was developed as a beginner data analytics portfolio project, with a focus on data preparation, data modeling, KPI calculations, and dashboard design.

## Dataset

- **Dataset:** Sample Superstore
- **Geographic coverage:** United States
- **Period covered:** 2014–2017
- **Records:** 9,994 rows
- **Original fields:** 21 columns

The dataset contains order-level information such as sales, profit, quantity, discounts, customer segments, product categories, regions, states, and shipping modes.

## Tools and Skills

- Microsoft Excel
- Power Query for data cleaning and transformation
- Power Pivot / Data Model for data modeling and relationships
- PivotTables and PivotCharts for analysis and visualization
- DAX measures for key performance indicators
- Excel dashboards, slicers, and timeline filters

## Data Preparation and Modeling

The data was prepared in Power Query and organized into a model consisting of:

- **Sales Fact table**
- **Customer Dimension**
- **Product Dimension**
- **Date Dimension**
- **Location Dimension**

The model was used to analyze sales and profit across different business dimensions. The original Product Name field was removed during the cleaning process, so this project focuses on category and subcategory analysis rather than individual product-name performance.

## Key Performance Indicators

The project includes measures for:

- Total Sales
- Total Profit
- Total Quantity
- Total Orders
- Total Customers
- Profit Margin
- Sales Growth %
- Profit Growth %

### Overall Results

| KPI | Result |
|---|---:|
| Total Sales | $2,297,200.86 |
| Total Profit | $286,397.02 |
| Profit Margin | 12.47% |
| Total Orders | 5,009 |
| Total Quantity | 37,873 |
| Total Customers | 793 |

## Dashboard Pages

### 1. Summary Dashboard

The Summary Dashboard presents a high-level view of business performance, including KPI cards, annual performance, category-level sales distribution, and key insights. Interactive filters help users explore the results.

### 2. Overview Dashboard

The Overview Dashboard provides additional detail through visualizations covering:

- Monthly sales and profit trends
- Profit by product subcategory
- Sales by state using a filled map
- Profit by discount level
- Sales and profit by shipping mode

The dashboards use Excel slicers and a timeline to support interactive exploration where connected to the relevant PivotTables and charts.

## Key Findings

- **Sales increased over the period:** 2017 sales were $733,215.26, up 20.36% compared with 2016.
- **Technology generated the highest category sales:** $836,154.03, approximately 36.4% of total sales.
- **Technology had the highest category profit:** $145,454.95, with a profit margin of 17.40%.
- **Furniture had a comparatively low profit margin:** 2.49%, despite generating $741,999.80 in sales.
- **The West region had the highest regional sales and profit:** $725,457.82 in sales and $108,418.45 in profit.
- **Some subcategories recorded losses:** Tables had a total profit of -$17,725.48, Bookcases -$3,472.56, and Supplies -$1,189.10.
- **Texas recorded the largest state-level loss:** -$25,729.36 in profit.

These findings describe patterns in the dataset. They do not establish causation or predict future performance.

## Repository Contents

The repository is intended to include:

| File | Description |
|---|---|
| `Superstore_BI_Dashboard.xlsx` | Excel workbook containing the analysis and dashboards |
| `Project_Overview.pdf` | Visual overview of the project and dashboards |
| `Dashboard_Demo.mp4` | Optional dashboard walkthrough video, if included |

## How to Use

1. Download or clone this repository.
2. Open `Superstore_BI_Dashboard.xlsx` in the desktop version of Microsoft Excel.
3. Navigate to the **Summary Dashboard** or **Overview Dashboard** worksheet.
4. Use the available slicers and timeline to explore the data.

Excel desktop is recommended because some workbook features, including Power Pivot/Data Model functionality and Excel map charts, may not be fully supported in other spreadsheet applications or Excel for the web.

## Notes and Limitations

- This is an analysis of the Sample Superstore dataset, not live business data.
- The dataset covers 2014–2017; findings should be interpreted within that period and dataset.
- The analysis identifies associations and trends, not causal relationships.
- Some supporting analysis areas may use helper tables or formulas and may require additional updating if the underlying data is replaced or extended.

## Project Links

- **Project Overview PDF:** [Add PDF link here]
- **Dashboard Demo:** [Add video link here]
- **GitHub Repository:** [Add repository link here]

---

Created by **Sama**  
Data Analytics Portfolio Project
