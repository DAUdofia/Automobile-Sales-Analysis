# Automobile Sales Performance Analysis

## Project Overview

This project analyzes automobile sales data to uncover sales trends, customer preferences, product performance, geographic opportunities, and profitability patterns.

The project uses an interactive Tableau dashboard and a Tableau story to communicate key findings and provide data-driven recommendations for improving business performance.

## Data Cleaning & Preparation

In the initial data preparation phase, we performed the following tasks:
1. Data loading and inspection.
2. Handling missing values and duplicates
3. Data cleaning and formatting
   
## Project Objectives/EDA

- Calculate average selling price per unit for each product category.
- Analyze total revenue trends over time.
- Compare sales performance across countries.
- Identify customer age segments contributing the most revenue.
- Evaluate profit margins across product subcategories.
- Compare customer gender distribution between high-revenue and low-revenue subcategories.
- Develop strategic recommendations to support sales growth and profitability.

## Tools and Technologies

- **Tableau:** Interactive dashboards, data visualization, and storytelling.
- **Microsoft Excel:** Supporting spreadsheet analysis and data handling.
- **Data Analytics:** KPI reporting, revenue analysis, profitability analysis, and customer segmentation.

## Key Performance Indicators

| KPI | Value |
|---|---:|
| Total Revenue | $94.69M |
| Total Profit | $41.91M |
| Overall Profit Margin | 44.26% |
| Total Units Sold | 1,333,705 |
| Total Transactions | 112,036 |
| Average Revenue per Transaction | $845.16 |

*Figures are reported in the project dashboard.*

## Key Findings

### 1. Revenue by Product Category

| Product Category | Revenue | Share of Revenue |
|---|---:|---:|
| Bikes | $68.83M | 72.69% |
| Accessories | $16.61M | 17.54% |
| Clothing | $9.25M | 9.77% |

Bikes are the primary revenue driver, accounting for approximately 72.69% of total revenue.

### 2. Average Selling Price per Unit

| Product Category | Average Selling Price |
|---|---:|
| Bikes | $1,901.70 |
| Clothing | $36.47 |
| Accessories | $16.99 |

Bikes have the highest average selling price per unit. The dashboard also shows that a higher selling price does not necessarily translate into a higher profit margin.

### 3. Profitability by Product Category

| Product Category | Revenue | Profit Margin |
|---|---:|---:|
| Accessories | $16.61M | 62.57% |
| Bikes | $61.83M | 40.38% |
| Clothing | $9.25M | 40.24% |

Accessories have the highest reported category profit margin, despite generating substantially less revenue than bikes.

**Business insight:** Bikes drive revenue, while accessories deliver a higher percentage profit margin.

### 4. Revenue by Customer Segment

| Customer Segment | Revenue |
|---|---:|
| Adults (30–49) | $53.31M |
| Young Adults (17–29) | $30.47M |
| Middle Aged (50–69) | $10.78M |
| Elderly (70–99) | $0.12M |

Adults aged 30–49 generate the highest reported revenue among the four customer segments. Young Adults aged 17–29 are the second-largest segment.

Together, these two segments account for approximately $83.78M in reported revenue.

### 5. Geographic Sales Performance

The dashboard highlights the following country-level revenue figures:

| Country | Revenue |
|---|---:|
| United States | $30.60M |
| Australia | $25.30M |
| United Kingdom | $11.02M |
| Canada | $7.98M |
| Germany | $9.96M |
| France | $9.83M |

The United States is the largest market, followed by Australia. Together, they contribute approximately 59% of total revenue.

The project considers six countries in total: Australia, Canada, France, Germany, the United Kingdom, and the United States.

### 6. Profit Margin by Subcategory

The analysis identifies substantial differences in profitability across product subcategories.

Selected reported margins include:

- Socks: 66.60%
- Fenders: 63.64%
- Road Bikes: 37.84%
- Touring Bikes: 37.84%
- Jerseys: 23.15%
- Caps: 22.22%

Road Bikes generate approximately $37.22M in revenue, making them a significant subcategory to investigate for profitability improvements. Jerseys and Caps also warrant further review because of their comparatively low reported margins.

### 7. Gender Distribution by Revenue Group

The project classifies subcategories generating above $500,000 in revenue as high-revenue subcategories and those below $500,000 as low-revenue subcategories.

| Revenue Group | Male Customers | Female Customers |
|---|---:|---:|
| High-revenue subcategories | 50.80% | 49.20% |
| Low-revenue subcategories | 51.45% | 48.55% |

The gender distributions are very similar across the two groups. This suggests that gender alone may not be a useful basis for distinguishing high- and low-revenue subcategories.

## Revenue Trends Over Time

The dashboard examines revenue from 2010 to 2017.

The reported findings indicate that revenue increased substantially over the period, with 2015 identified as the strongest full year at approximately $22.32M.

The report highlights growth from approximately $10.05M in 2011 to $22.32M in 2015.

## Strategic Recommendations

1. **Protect the leading revenue category:** Maintain the performance of bikes by reviewing customer demand, product preferences, and sales trends.
2. **Increase accessory cross-selling:** Consider bundling helmets, gloves, bottles, and bike racks with bike purchases to explore opportunities for additional revenue.
3. **Focus on key customer segments:** Investigate the purchasing behavior of customers aged 30–49 and 17–29 to inform targeted marketing.
4. **Investigate low-margin subcategories:** Review supplier costs, pricing, and promotional strategies for products such as Caps and Jerseys.
5. **Improve Road Bike profitability:** Because Road Bikes generate substantial revenue, even a modest margin improvement could have a meaningful impact on total profit.
6. **Explore geographic growth opportunities:** Protect performance in the United States and Australia while investigating opportunities in other markets.
7. **Avoid relying on gender alone:** Consider age, country, product preferences, and purchasing behavior when developing customer segments.

These recommendations are based on patterns identified in the dashboard and should be evaluated alongside additional operational and customer information.

## Limitations/Actions taken 

**Limitation:**
For the Objective **(*- Identify customer age segments contributing the most revenue.*)**. Customer Age was not segmented which made it impossible to make that analysis.

**Actions Taken:**
I had to create a new *calculated field* named (customer segment) and customer ages where distributed thus:
| Age Range | Aliases |
|---|---|
| 17 - 29 | Young Adults |
| 30 - 49 | Adults |
| 50 - 69 | Middle Age |
| 70 - 99 | Elderly |

## Conclusion

This project demonstrates how sales data can be transformed into actionable business insights through KPI analysis, visual storytelling, and interactive dashboards.

The findings highlight the importance of balancing revenue growth with profitability, understanding customer segments, monitoring geographic performance, and investigating products with substantial revenue but opportunities for margin improvement.

## Author
**DAUdofia**

**Aspiring Data Analyst | Business Intelligence | Data Visualization**

Passionate about turning data into insights that support smarter business decisions.
