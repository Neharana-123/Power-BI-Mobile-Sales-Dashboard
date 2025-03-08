# Power-BI-Mobile-Sales-Dashboard
This Mobile Sales Dashboard is an interactive Power BI report designed to analyze mobile phone sales performance across different cities, brands, and models. The dashboard provides key insights into total sales, total quantity sold, transaction counts, and average pricing trends.

# Key Features
•	KPI Cards: Displays total sales, total quantity sold, total transactions, and average price per unit.
•	Sales by City: A map visualization showing sales distribution across different cities.
•	Monthly Sales Trends: Line chart tracking sales quantity per month.
•	Payment Method Breakdown: Pie chart displaying transactions by payment methods (UPI, Debit Card, Credit Card).
•	Sales by Brand & Model: Bar charts for total sales segmented by brand and mobile model.
•	Customer Ratings Analysis: Bar chart showcasing customer feedback categorized as Good, Average, and Poor.
•	Sales by Day: Line chart illustrating sales trends by days of the week.
•	MTD (Month-to-Date) Analysis: Line chart visualizing total sales progress for the current month.
•	Same Period Last Year Analysis: Tables and column charts comparing current performance against the same period in the previous year.

# Tools & Technologies Used
•	Power BI: Data visualization and dashboard creation
•	Data Cleaning & Transformation: Power Query
•	DAX (Data Analysis Expressions): For calculated measures and KPIs.

# Dataset
•	The dataset contains information on mobile sales, the columns in the dataset are – Transaction ID, Day, Month, Year, Day name, Brand, Unit Sold, Price per unit, Customer Name, Customer Age, City, Payment Method, Customer Ratings and Mobile Model.
•	Created New Calculated Column named Rating Status (Good,Average,Poor) using a DAX formula .
•	Merged Day, Month, Year column to one column Named Date.
•	Created New Measures – Average Price, MTD ,Same Period Last Year, Total Quantity, Total Sales and Total Transactions.
•	Created a Custom Calander Separately.

