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

## Recommendations
(To be added)

## Next Steps
(To be added)

## Tools Used
- Power BI
- DAX
- SQL
- Python
