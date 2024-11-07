## Finance Report Dashboard

This is a power BI Financial Dashboard buid to analyze financial data. 
The dashboard provides insights into various financial metrics such as total sales, profit, profit margins, and sales by segments and countries. It is designed to offer a quick overview of financial performance using interactive visualizations.

### The main objectives of this report is to:

To visualize financial data for better decision-making.
To track key performance indicators (KPIs) such as sales, profit, and discounts.
To provide actionable insights using interactive charts and filters.

### Key DAX Measures:

Several custom DAX measures were used to enhance the insights provided by the dashboard:

Total Sales: SUM(financials[Net Sales])

Total Profit: SUM(financials[Profit])

Profit Margin: DIVIDE(SUM(financials[Profit]), SUM(financials[Net Sales]), 0)

Year-over-Year (YoY) Sales Growth: Compares sales growth year over year using DAX.

Visualizations Used:

Bar Charts: To compare sales and profit and discount by product and category.

Line Charts: To show sales trends over time (monthly and yearly).

Pie Charts: To visualize the distribution of sales across different market segments.

Map: To visualise distribytion of sales by countries

KPI Cards: For key metrics like total sales, total profit, total quantity and total discount.

Slicers: To filter data by Time period - Year and Month.

### Usage:

Exploring the Dashboard: Use the slicers and filters to narrow down data by specific countries, products, or time periods.

Interactivity: Click on visuals to interact and drill down into specific segments or products.
