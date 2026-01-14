# Retail Sales & Profitability Analysis (Superstore)

## Overview

This project presents and end-to-end analysis of retail sales and profitability using the Superstore dataset. The analysis focuses on understanding overall business performance and identifying key customer and product drivers, evaluating regional profitability, and analyzing growth trends over time.  
An interactive Power BI dashboard was built to support exploratory analysiss and executive level decision making. The project emphasizes not just visualization, but also business insights and actionable recommendations derived from the dataa.

## Business Problem

The objective of this analysis is to evaluate sales and profitability performance of a retail superstore and identify key business drivers across customers, products, region and time.

Specifically, this analysis aims to answer the following questions:
- How are sales and profit trending over time?
- Which customers and products contribute the most to revenue and profir?
- Are there regions or categories generating high sales but low profitability?
- Is the business experiencing healthy year-over-year-growth, and what is driving it?

The insight from this analysis are intended to support data-driven decision making around pricing, discounting, product strategy, and regional focus.

## Dataset

The analysis is based on the superstore retial dataset, which contains historical order level transaction data.

Key characteristics of the dataset:
- Granularity: One row per order line item.
- Time-based fields: Order date, ship date.
- Business metrics: Sales, profit, quantity, discount.
- Dimensions: Customer, product, category, sub-category, segment, region, and state.

The dataset represents typical retail operations and is suitable for analyzing sales performance, profitability patterns, and growth trends.

## Data Preparation & Modeling
The dataset was prepared and modeled to support efficient analysis and time-based insights.

Key steps included:
- Cleaned and validated the data by checking for missing values, incorrect data types, and incosistent fields.
- Created a Date table to enable time intelligence analysis such as monthly trends and year-over-year (YoY) comparisons.
- Estabalished a star schema with the orders table as the fact table and customer, product, and date tables as dimensions. 
- Defined core business measures such as Total Sales, total profir, Order COunt, average order value, profit margin using dax.
- Implemented time intelligence measures including sales YoY%, profit YoY%, and comparisons against the previous year.
- Used field parameters to allow dynamic switching Sales and Profir across selected visuals for better interactivity.

This modeling approach ensured scalability, consistent calculations, and improved performance of the Power BI report.

## Analysis & Key Insights
The analysis was strucutred into four sections, each addressing a specific business perspective and decision-making need. 

### Page 1 - Executive Overview

The Executive overview focuses on overall business performance and high-level trends.

#### Key insights:
- Sales and Profit show clear seasonal patterns, with peak performance during specific months, indicating strong time based demand cycles.
- While sales demonstrate consistent growth over time, profit trends reveal periods of volatility, suggesting that revenue growth doesnt always translate into proportional profitability.
- Category-level analysis sows that a small number of Categorieas contribute a significant share of total sales and profit.
- Regional analysis highlights differences in performance, wuth some regions generating high sales volumes but comparatively lower profit margins.

These insights indicate the importance of monitoring profitability alongside revenue, rather than relying on sales figures alone.

### Page 2 - Customer & Product insights

This section analyzes how customers and products drive business performance.

#### Key insights:
- A small subset of customers contributes disproportionately to total sales, indicating revenue concentration among top customers.
- Similarly, a limited number of products account for a large share of overall sales, following a Pareto-like distribution.
- Segment-level analysis shows variations in sales contribution across customer segments, highlighting differences in purchasing behavior.
- Profitability by sub-category reveals that not all high-selling products are equally profitable, with certain sub-categories generating lower margins despite strong sales performance.

These findings suggest opportunities to strengthen customer retention strategies for high-value customers and reassess pricing or discount strategies for low-margin products.

### Page 3 - Geographical Analysis

The geographical analysis focuses on regional and state-level performance.

#### Key insights:
- Sales and profit distribution varies significantly across regions, indicating uneven business performance geographically.
- Certain states contribute high sales volumes but show relatively low profit margins, suggesting potential inefficiencies such as higher discounts or operational costs.
- The comparison of sales, profit, and profit margin at the state level helps identify regions where revenue growth may not be sustainable from a profitability standpoint.

This analysis highlights the need for region-specific strategies rather than a uniform national approach.

### Page 4 - Trends and Growth

This section evaluates business growth and the quality of that growth over time.

#### Key insights:
- Year-over-year analysis shows overall growth in sales, indicating business expansion compared to the previous year.
- Growth is not uniform across categories, with certain categories driving most of the YoY increase.
- The comparison between profit trends and order volume reveals whether growth is driven by increased demand or changes in profitability per order.
- Periods where order volume increases faster than profit suggest margin pressure, while periods of stable order volume with rising profit indicate improved operational efficiency.

These insights help assess whether growth is healthy and sustainable, rather than driven purely by volume.


## Recommendations

Based on the analysis, the following recommendations can help improve overall business performance and profitability:

- Prioritize profitability alongside revenue by closely monitoring profit trends, especially during high-sales periods where margins show volatility.
- Focus retention and relationship-building efforts on high-value customers who contribute a disproportionate share of total sales.
- Review pricing and discounting strategies for sub-categories that generate strong sales but consistently low profit margins.
- Adopt region-specific strategies for states and regions that show high sales volumes but weaker profitability, rather than applying uniform national policies.
- Invest further in high-growth and high-margin categories to sustain healthy year-over-year growth.

These recommendations aim to balance growth with profitability and support data-driven decision-making across key business areas.


## Next Steps

This analysis is based on historical transactional data and does not account for external factors such as marketing spend, operational costs, or customer acquisition costs.

#### Potential next steps include:
- Incorporating cost and discount data at a more granular level to better understand margin drivers.
- Performing customer lifetime value (CLV) analysis to evaluate long-term customer profitability.
- Adding forecasting models to project future sales and profit trends.
- Conducting cohort or basket analysis to better understand customer purchasing behavior.

These extensions would enable deeper insights and more advanced strategic decision-making.


## Tools Used
- Power BI
- DAX
- SQL
- Python
