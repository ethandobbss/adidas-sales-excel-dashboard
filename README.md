# Adidas Sales Excel Dashboard


![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)
![Microsoft Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)

![Dashboard](assets/dashboard.png)

---
## Problem Description

Raw sales data on its own doesn't tell a clear story, it's hard to see where revenue is concentrated or how retailers and regions compare. This project turns a large volume of raw Adidas sales data into a clean, easy-to-read Excel dashboard that surfaces those trends at a glance.

## Dataset Information

The dataset was sourced from Kaggle, and can be found in data/. You can find the exact dataset I used [here](https://www.kaggle.com/datasets/heemalichaudhari/adidas-sales-dataset).

## Design Rationale

The main page includes a File Index acting as a table of contents, and every page has a navigation button linking back to it.

![Index](assets/index.png)

Each pivot table page also includes a text box explaining the purpose and significance of that specific table, giving context to the data being shown.

![SalesRegions](assets/SalesRegions.png)

Each tab is named directly after the pivot table it contains, so anyone navigating the file can immediately tell what question that page answers without needing to open it first. This intentional 1:1 naming between tabs and tables keeps the workbook easy to navigate, even without the nav buttons.

- Top Products by Sales & Profit: identifies which products drive volume versus which are most profitable per unit
- Retailers (Sales vs Profit): compares revenue and profitability across retail partners to spot where sales convert efficiently into profit
- Sales Method: breaks down revenue by in-store, online, and outlet channels to understand where sales are concentrated
- Sales Regions: displays geographic concentration of sales at the state level
- Sales Trend: tracks sales over time to reveal seasonal patterns and growth trends

Each pivot table was built to answer a specific business question rather than just summarize data for its own sake. Together they give a well-rounded view of where revenue comes from, what's driving it, and how it's changing over time.

## Outcome

The final product is the Excel dashboard, which you can view [here](excel/Adidas-Excel-Project.xlsx). This dashboard equips executive management with a clear, data-driven view of sales performance, allowing for more informed decision-making. Actionable steps management could take include:

- Prioritize Foot Locker and Amazon: both show the strongest sales-to-profit conversion, while other retailers lag in profitability despite volume.
- Investigate the online sales gap: online accounts for just 3% of sales versus 62% in-store, an unusually wide gap worth examining for missed growth opportunity.
- Plan for the Q4 seasonal spike: sales consistently surge in November-December each year, supporting proactive inventory and staffing decisions.

## Business Insights

This section presents key business questions the dashboard answers, along with the insights they reveal.

### 1. How did Adidas's monthly sales perform across 2020 and 2021?
Sales were volatile in 2020, ranging from a low of about $1,816.70K to a high of $10,585.11K, then trended upward through 2021, closing the year at a peak of $23,370.50K in December- the highest point on the entire chart. This shows steady month-over-month growth into year-end 2021.

### 2. Which sales channel contributes the most to total revenue?
Per the donut chart, In-store sales dominate at 62% of total sales, Outlet accounts for 35%, and Online is minimal at just 3%. In-store is clearly the primary revenue driver, with online being a very small piece of the mix on this dashboard.

### 3. Which retailer delivers the highest cumulative sales and profit?
The Retailers Sales & Profit chart shows profit climbing across retailers, with West Gear at $12,522.17K, Amazon at $13,398.86K, and Foot Locker topping the chart at $23,914.66K, the highest combined sales-and-profit contribution among all six retailers shown (Walmart, Kohl's, Sports Direct, West Gear, Amazon, Foot Locker).

### 4. Which product category sells the most units and generates the most sales?
In the Top Products chart, Men's Street Footwear has the tallest bars for both units sold and total sales, clearly outperforming the other five categories (Men's Apparel, Men's Athletic Footwear, Women's Apparel, Women's Athletic Footwear, Women's Street Footwear). Women's Apparel is the second-strongest performer by bar height.

### 5. What time period and product/region scope does this dashboard cover?
The filter panels show Years: 2020 and 2021 both selected, all six Product categories available (Men's/Women's Apparel, Athletic Footwear, Street Footwear), and all five Regions (Midwest, Northeast, South, Southeast, West) included- confirming the dashboard reflects the full two-year, all-region, all-product dataset rather than a narrowed slice.

## Future Enhancements

Here are some ideas I would explore if I kept building this project further:

- I would add a profit margin analysis, calculating profit margin (Operating Profit ÷ Total Sales) to identify which retailers or products convert sales into profit most efficiently, not just which generate the most revenue.
- Create a darkmode variant to reduce eye strain.

## Contact Information

You can contact me via email at [ethan-jacob@comcast.net](mailto:ethan-jacob@comcast.net) or connect with me on [LinkedIn](https://www.linkedin.com/in/ethan-dobbs).

Thank you for reviewing my Adidas Excel Dashboard Project! It demonstrates my ability to transform raw sales data into an interactive, business-focused dashboard.

## License

This project is licensed under the [MIT License](LICENSE).
 
