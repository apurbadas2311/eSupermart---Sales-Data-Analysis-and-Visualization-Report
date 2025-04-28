eSupermart - Sales Data Analysis and Visualization Report
e-supermart is a data analysis and visualization project centered around sales data, likely originating from a retail or e-commerce business. The primary goal of the project is to derive meaningful insights into sales performance, customer behavior, and product trends. The analysis leverages tools such as PowerBI to process and present the data in an understandable format.

Key Features
The project delivers several key features:

• Sales Analysis: In-depth analysis of sales figures, profit margins, and order volumes.

• Regional Analysis: Breakdown of sales and profit data by geographical region.

• Customer Analysis: Examination of sales performance based on customer names and customer ratings.

• Product Analysis: Sales analysis categorized by product category and sub-category.

• Time-based Analysis: Analysis of monthly sales and profit trends.

• Key Metrics: The project focuses on several key performance indicators (KPIs):

    o	Total Sales

    o	Total Orders

    o	Average Customer Rating

    o	Profit and Profit Percentage
Data Sources
The project utilizes the following data sources:

• SuperMart-SalesTable: Contains detailed information about individual sales transactions.

• SuperMart-DateTable: Provides a structured set of dates for time-based analysis.

• SuperMart-ProductTable: Includes information about the products being sold.

Data
• The data files are located in the data/ directory. Ensure these files are present. If the data is not in CSV format, conversion may be necessary.

Expected Results and Visualizations
The project is expected to deliver the following results and visualizations:

• Total Sales and Profit by Month: A line chart illustrating the trend of total sales and profit over time, potentially with a year filter to analyze seasonality and business growth.

• Sales by Product Hierarchy: A breakdown of sales by product category and sub-category, possibly using a tree map or bar chart, to highlight revenue-driving products.

• Total Sales by Region: A geographical map or bar chart displaying sales performance across different regions to identify strong and weak markets.

• Total Sales by Customer Name: A bar chart ranking customers by total sales value, useful for identifying key accounts.

• Average Customer Rating: An analysis of customer rating distribution, such as a histogram or average rating by customer segment.

• Key Performance Indicators (KPIs):

   o	Total Sales: Overall revenue generated.

   o	Total Orders: Number of transactions.

   o	Profit and Profit %: Profitability metrics.

   o	Average Rating: Customer satisfaction metric.
The specific visualizations are to be created using PowerBI, and the sales_dashboard.pbix file in the visualizations/ directory should contain these. If Python and Jupyter Notebooks are used, the sales_analysis.ipynb notebook will contain the code to generate these results, with visualizations potentially saved as images in the visualizations/ directory.

Technologies Used
• Data Analysis Tool: PowerBI

• Data Format: Excel

