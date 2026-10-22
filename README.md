# PowerBi-sales-dash
# 📊 Sales Performance Dashboard

 1. Project Title
**Sales Performance Dashboard: Power BI**

2. Short Description
A Power BI dashboard that analyzes wholesale scale-model vehicle sales (2,823 order lines, 307 orders, about $8.29M in revenue) across 7 product lines, 19 countries and 4 territories. It shows which products, regions and deal sizes drive revenue.

 3. Tech Stack
- **Power BI Desktop**: data modeling and visualization
- **DAX**: calculated measures (Total Sales, Total Quantity, Order Count, Avg Order Value)
- **Power Query**: data loading and type correction
- **Claude AI**: used to speed up data modeling, measure creation and analysis
- **Excel / CSV**: source data format

4. Data Source
- Sales order dataset (`vo_1111`) with 2,823 order lines and 17 columns
- Orders from **January 2012 to August 2017**
- Fields include order number, quantity, unit price, order and delivery dates, status, product line, city, state, country, territory, customer contact, deal size and sales amount
- Source:Kaggle "Sales Data Sample"]

5. Features & Highlights
- **Key metrics:** Total Sales ($8.29M), Total Quantity (99,067 units), Order Count (307) and Avg Order Value (about $27,006)
- **Product mix:** Classic Cars lead with about **$2.97M (36% of sales)**; Classic and Vintage Cars together make up about **55%** of revenue
- **Wide coverage:** 7 product lines, 19 countries, 4 sales territories and 6 order statuses
- **Deal size analysis:** orders grouped into Small, Medium and Large deals
- **Data quality fixes:** converted `salesamount` from text to a numeric currency field, and stopped ID columns (order number, order line number) from being summed in visuals
- **Reusable DAX measures** organized in a "Key Measures" folder
- Interactive filtering by product line, territory, status and date

 6. Problem Solved
Sales data sitting in raw order records makes it hard to see **what is selling, where, and how well**. This dashboard turns that data into clear KPIs and visuals, so decision-makers can quickly identify top-performing products and regions, spot weak areas such as low-selling lines like Trains, and track order status, supporting better inventory, pricing and sales strategy decisions.
