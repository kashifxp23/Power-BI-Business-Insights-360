# Business-Insights-360 - Power BI Project

## Overview  
This Power BI project offers a detailed analysis of business performance across departments including sales, finance, marketing, and supply chain. Through interactive dashboards and insightful visualizations, the project enables stakeholders to monitor KPIs, identify trends, and make data-informed strategic decisions.

## Problem Statement  
AtliQ Hardware, despite its rapid growth, faced significant financial losses in the LATAM region due to reliance on Excel-based analytics and intuition-driven decisions, because of inefficiencies, lack of real-time insights, and increased potential for human error. This project was developed to overcome these challenges by centralizing data from multiple sources into a unified, interactive Power BI dashboard. The objective is to provide business leaders with an intuitive, real-time view of operations and performance, enabling them to identify bottlenecks, evaluate performance gaps, and uncover growth opportunities.

## Project Highlights  
- **Home Page**: Acts as the central navigation panel for accessing each business domain easily.  
- **Finance View**: Tracks financial KPIs, revenue trends, gross margin, and profitability.  
- **Sales View**: Provides insights into product and customer performance, along with year-over-year comparisons.  
- **Marketing View**: Analyzes campaign effectiveness, channel-wise contribution, and segment performance.  
- **Supply Chain View**: Monitors inventory flow, delivery timelines, and logistical performance.  
- **Executive View**: A summarized view tailored for decision-makers to track top-level metrics and trends.

## Methodology  
1. **Data Collection**: Data was imported from a MySQL database covering key business dimensions and metrics.  
2. **Data Cleaning**: Inconsistencies, null values, and duplicates were addressed using Power Query.  
3. **Data Modeling**: A star schema was implemented by relating fact and dimension tables to ensure an efficient data model.  
4. **DAX Calculations**: Key performance metrics were derived using calculated columns and measures in DAX.  
5. **Dashboard Development**: Designed clean, interactive pages with slicers, dynamic titles, and visual KPIs.  
6. **Deployment**: Report was published to Power BI Service with scheduled auto-refresh using a personal data gateway.

## Files and Resources  
- **Live Power BI Dashboard**: [Click to View](https://app.powerbi.com/view?r=eyJrIjoiMzZmMDJhZWQtMDU3ZC00NmY4LTlmNDMtMDI1YWQ5NTQ5YjgwIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)
- **Project Report (PDF)**
  
## Tools & Technologies Used  
- Power BI Desktop and Service  
- MySQL  
- Excel  
- DAX Language  
- DAX Studio  
- M Language (Power Query)

## Key Power BI Techniques Applied  
- Data modeling using star schema  
- Creating measures with DAX  
- Dynamic titles and filter-based visuals  
- Conditional formatting  
- Bookmarks for toggling views  
- Navigation using buttons  
- Creation of custom date tables  
- Scheduled data refresh via gateway  
- Workspace management and permissions in Power BI Service

## Business Terms Used  
- Gross Price  
- Pre-invoice Deductions  
- Post-invoice Deductions  
- Net Invoice Sale  
- Gross Margin  
- Net Sales  
- Net Profit  
- COGS (Cost of Goods Sold)  
- YTD (Year to Date)  
- YTG (Year to Go)

## Conclusion  
This Power BI project successfully transforms raw business data into meaningful insights, providing a unified and real-time view of organizational performance. It helps decision-makers track key metrics, improve operational efficiency, and make strategic decisions based on accurate, up-to-date data.
