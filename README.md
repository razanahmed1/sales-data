# 📊sales-data Dashboard 

## 📌About the Project
A comprehensive Power BI dashboard analyzing orders and sales from October 2024 to September 2025. Includes KPIs, shipping status, city-wise sales distribution, and top-performing product categories.

## 🎯 Objective 

Develop an interactive Power BI dashboard that visualizes sales metrics, order details, product categories, and city‑level performance to support data‑driven decisions.

## 🔍Project Features
* Interactive dashboard presenting clear visual insights into sales and order performance
* Monthly sales trend analysis through a line chart showing sales patterns across the year
* Key Performance Indicators (KPIs) including Total Sales, Total Profit, and Orders Count
* Shipping status analysis using a pie chart showing Delivered, In Transit, and Ready‑to‑Deliver orders
* Product category comparison to identify top‑selling categories
* Interactive map displaying city‑level sales distribution
* Detailed orders table including Order ID, customer info, product details, cost, profit, and sales
* Dynamic filters (Date, City, Product Category) for customized data exploration
* Clear navigation between the Overview page and the Orders Details page
  
## 🛠️Tools Used
* Power BI – For building the interactive dashboard and visualizing key insights.
* Power Query – For cleaning, transforming, and preparing the data.
* DAX (Data Analysis Expressions) – For creating measures and advanced calculations.
* Excel – For organizing and preprocessing the raw data before importing it into Power BI.
* Data Modeling – For designing table relationships and creating a structured analytical model.

  ## 🗂️ Data Structure

Main Tables

| Table Name        | Description                               | Key Columns                                                                 |
|-------------------|---------------------------------------------|-------------------------------------------------------------------------------|
| Orders Table      | Contains all order-level details            | OrderID, Customer Info, Product ID, Product Category, Product Name, Total Cost, Total Profit, Total Sales |
| Date Table        | Used for time-based analysis                | Date, Year, Month, Quarter                                                   |
| Customers Table   | Contains customer information (if included) | Customer ID, Customer Name, City                                             |
| Products Table    | Contains product details (if included)      | Product ID, Product Name, Product Category                                   |



Relationships

| From Table | To Table   | Relationship Type |
|------------|------------|-------------------|
| Orders     | Date       | Many-to-One       |
| Orders     | Customers  | Many-to-One       |
| Orders     | Products   | Many-to-One       |

  ## 🖼️ imaage Project
  
  ![image here](https://res.cloudinary.com/dhlxcif1m/image/upload/v1766932967/fzqbiv0j6jsaudkv4qkd.png)
  ![image here](https://res.cloudinary.com/dhlxcif1m/image/upload/v1766933077/vp4pexubdmydbwum29h6.png)
  
## 📁 Files 

-  contains raw data, analysis, and charts
  -   [https://drive.google.com/drive/folders/1YirPlbZsUfA7MHCKsRTrcAirij_KxIzS?usp=drive_link](https://drive.google.com/drive/folders/1sj39OKOA2U2Nhi1MnYqpwBZAr5H2HE5P?usp=drive_link)

## 🚀 Future Enhancements

* Add advanced DAX measures for deeper business insights.
* Implement predictive analytics to forecast future sales trends.
* Expand the dashboard with additional pages (e.g., Customer Insights, Product Performance).
* Integrate more data sources to enrich the analysis.
* Add drill‑through pages for detailed order and customer exploration.
* Improve the data model with more dimensions (e.g., Region, Supplier).
* Automate data refresh for real‑time updates.
