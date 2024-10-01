NorthWind Trades Dashboard
Project Overview

This project aims to analyze sales and order trends using the NorthWind dataset from [Maven Analytics](https://drive.google.com/file/d/156QeDIl7t6gbDLqD3hvrx5KgTahdLQT3/view?usp=sharing). The data has been transformed, modeled, and visualized in Power BI to provide key business insights such as sales performance, order quantities, shipping distribution, and customer behavior.
Key Features

    Data Transformation:
        Applied necessary transformations such as cleaning, filtering, and formatting.
        Converted raw data into meaningful dimensions and facts for analysis.

    Data Modeling:
        Implemented a star schema with fact and dimension tables.
        Created a DimDate table for handling date hierarchies.

    DAX Measures:
        Defined custom DAX measures for calculating total sales, number of orders, average quantity, max/min quantity, and employee performance metrics.

    Visualizations:
        Cards: Display total sales, number of orders, average quantity, maximum quantity, and minimum quantity.
        Line Chart: Shows the sales trend over time (orders, shipped orders, delivered orders).
        Column Chart: Ranks the most ordered products by quantity (sorted in descending order).
        Treemap: Visualizes product categories and individual products within those categories, showing the distribution of sales.
        Pie Chart: Illustrates the distribution of orders by shipping company.
        Waterfall Chart: Represents employee performance by gross sales over the years.
        Top 5 Customers: A bar chart showing the top 5 customers based on the number of orders.
        Map Chart: Visualizes sales by country.
        Line Chart: Combines #orders by order date, ship date, and required date in one visual for time-based analysis.

    Other Features:
        Implemented slicers to filter by country and categories.
        Added bookmarks and tooltips for enhanced navigation and detail-level insights.
        Included page navigators to switch between dashboards.
        Used Quick Measures and the Q&A visual to allow for intuitive, user-driven questions about the dataset.

How to Use

    Page 1:
        This page provides an overview of sales, shipping companies, and product performance.
        Key metrics such as total sales and number of orders are displayed on cards for quick reference.
        Line and pie charts offer detailed breakdowns of orders, shipping, and sales.

    Page 2:
        This page dives deeper into sales by category, top customers, and employee performance.
        The treemap and column charts offer insights into the product hierarchy and most ordered items.
        A bar chart shows the top customers by number of orders.

    Interactive Features:
        Use slicers to filter results by country.
        Hover over the visuals for tooltips showing detailed information.
        Switch between pages using the page navigator at the bottom of the report.

    Bookmarks:
        Utilize bookmarks to jump between pre-configured views or reset filters to default settings.
