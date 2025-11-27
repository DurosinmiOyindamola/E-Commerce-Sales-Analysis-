# E-Commerce-Sales-Analysis-
## Table Of Content
- [Project Overview](#projectoverview)
- [Objectives](#objectives)
- [Data Description](#datadescription)
- [Process](#process)
- [Tools Used](#toolsused)
- [Key Insights](#keyinsights)
- [Conclusion](#conclusion)
### Project Overview
This project analyze online store sales data. It provides insights into revenue, sales trends, top-performing products, and customer behavior. The dashboard helps stakeholders make data-driven decisions to optimize sales, inventory, and marketing strategies.

### Objectives
The main objectives of this analysis are to:
- Analyze overall sales performance and revenue trends.
- Identify top-selling products and categories.
- Understand customer purchase patterns.
- Track monthly and seasonal sales trends.
- Provide actionable insights to improve business strategy and sales performance.

### Data Description
- Sales Data (Fact Table): 1,000 rows and 9 columns including PaymentKey, Itemkey, Storekey, Customerkey, DateKey, Quantity, UnitPrice, Totalprice and unit
##### Dimension Tables:
- ITEMS: Itemkey, ItemName, Description, Unitprice, Supplier, Mancountry
- STORE: Storekey, Divison, District
- CUSTOMERS: Customerkey, CustomerName, Contact_no, Nid
- TIME: DateKey, Date, Month, Quarter, Year, Week, Hour, Day,
- TRANSACTION: Transactionkey, Transaction_type, Bankname
### Tools Used
- Microsoft Excel: calculations, Pivot Tables, and dashboard creation
- Power Query :For cleaning and transforming the data
- DAX / Excel Formulas – For calculating key metrics and KPIs
### Process
- Data Preparation: Cleaned and transformed raw CSV/Excel data.
- DAX Calculations: Created measures for year-over-year comparison and performance analysis.
- Used Pivot Tables to compute totals and performance KPIs
- Applied slicers for product category, region, and year
- Dashboard Design: Added Pivot Charts for visualization and arranged them into a clean dashboard layout.
### Key Insights
- The company recorded $105M in total revenue and 6M units sold, reflecting a 16.1% year-over-year increase.
- Despite strong sales, customer growth remained flat (0%), indicating that revenue increases were driven by existing customers.
- Top Performing Markets: Germany, Poland, Lithuania, Bangladesh, and India contributed most to revenue.
- Best-Selling Products:
- Ct : 2M units
- Cans : 1M units
- Bottles : 840K units
- Oz : 454K units
- Bags : 367K units
- The average selling price across all products is $17.6 per unit.
- Engagement levels remained stable, with no noticeable increase even though revenue grew significantly.
### Conclusion
This E-Commerce Excel Dashboard provides a powerful overview of business performance using Pivot Tables and DAX. It helps stakeholders understand sales trends, customer behavior, and year-over-year growth to support strategic decisions.
