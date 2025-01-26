# Atliq Hardwares Business-Insights-360


## Context :

        Atliq Hardwares is a fast-growing electronics company that sells products such as PCs and printers to customers through various platforms like Croma and Amazon, as well as through channels such as retailers, direct stores, and distributors.

## Problem Statement :

        Atliq Hardwares has experienced significant losses after opening its own store in the Latin America region. This decision was primarily driven by outdated Excel-based analytics and assumptions drawn from surveys. To address this issue, the company recognized the need to establish an analytics team and adopt a transformative approach to leverage data for informed decision-making.

## Datasets Overview:

Before diving into the analysis, it is crucial to understand the datasets. The data consists of two main types of tables:

**Dimension table:** These tables contain static data, such as customer and product details.

**Fact table:** These tables hold transactional data for analysis.

gdb041:
* dim_customer
* dim_market
* dim_product
* fact_forecast_monthly 
* fact_sales_monthly 

gdb056:
* freight_cost
* gross_price
* manufacturing_cost
* Pre_invoice_dedutions
* Post_invoice_deductions


### Importing Data and Data Modeling:

The data was imported from MySQL into Power BI, where it was cleaned, transformed, and used to create a data model.

In this project, we utilized the Snowflake schema data modeling method to structure the data effectively.


![Datemodelling](https://github.com/user-attachments/assets/7181e67a-5ea9-45f4-95f0-9613f2f7c778)

## Power Bi Skills Learned:

*Fundamentals of Power BI 
*Date cleaning and Data validation 
*Data Modelling techniques like star and snowflake schema
*Creating calculated columns and DAX measures
*Learnt how to use bookmarks
*Implementing custom tooltips 
*Creating dynamic Titles
*Publishing reports to PowerBI Services
*Setting up a personal gateway for automatic data refresh

### Tools Used:

Project Charter 
SQL
Power BI Desktop
DAX studio (for reducing file size),

## Power BI Dashboard Overview:

### Home Page: The landing page serves as the entry point to the dashboard. It includes buttons that allow users to navigate seamlessly to different pages.

![Home Page](https://github.com/user-attachments/assets/9b597502-4900-49a0-8d8b-53894bee09c6)

### Finance Page: Highlights key KPI metrics such as net sales, gross margin %, and net profit %. It includes visuals like the profit and loss statement, net sales performance over time, and an analysis of top/bottom products and customers by net sales.

![Finance View](https://github.com/user-attachments/assets/1d385d4c-1179-47d7-971c-dff16b886fb3)


### Sales Page: Features key visuals related to sales, such as customer and product performance, along with performance metrics based on net profit %, gross margin %, and unit economics.

![Sales View](https://github.com/user-attachments/assets/93c7f0c3-8236-418f-91d4-2a7531768d88)


### Marketing Page: Includes key visuals highlighting product performance and customer performance segmented by region and market.

![Marketing View](https://github.com/user-attachments/assets/a1871d8f-948b-42af-bcf3-4bf94a753f65)


### Supply Chain Page: Showcases product and customer performance using key KPI metrics such as forecast accuracy %, net error, and absolute error %.

![Supply Chain View](https://github.com/user-attachments/assets/c7a246b2-3db7-401c-be45-b9d466bd90c0)


### Executive Page: Provides a high-level overview of the company's performance by consolidating essential KPIs and metrics from all other views.

![Executive View](https://github.com/user-attachments/assets/afc95ab2-2706-4ead-a4bb-faf035aec9f9)

## Conclusion :

This report enables stakeholders to perform in-depth data analysis and make informed, data-driven decisions to drive business growth.
