# pandas-sales-visualizer
# Objective
Analyze sales data from a CSV file to generate business insights and visualize trends using Python, Pandas, and Matplotlib.

# Tools Used
Python 3.x – Core programming language
Pandas – Data loading, cleaning, and aggregation
Matplotlib – Data visualization

Google Colab – Running the analysis

# Dataset
sales_data_50.csv is the dataset
Date – Random date within the year 2025
Month – Month name extracted from the date
Product – Randomly chosen from a list of products (Laptop, Mobile, Tablet, Headphones, Smartwatch)
Sales – Random sales value between 500 and 3000

# Example Rows:

Date	Month	Product	Sales
2025-01-05	January	Laptop	1500
2025-02-18	February	Tablet	600

# Analysis Performed
1️. Sales by Product
-Grouped by Product
-Aggregated using sum of sales
-Visualized with a Bar Chart

2️. Sales by Month
-Grouped by Month
-Sorted in calendar order for accuracy
-Visualized with a Line Chart showing trends

3️. Product Sales Share
-Pie Chart showing percentage contribution of each product to total sales

4️. Sales Distribution
-Boxplot per product to detect outliers and understand variability

# Visualizations Generated
Bar Chart – Total Sales by Product
-Shows the best and worst-selling products.
-Line Chart – Monthly Sales Trend
-Identifies sales peaks and dips over time.
-Pie Chart – Product Sales Share
-Shows how total sales are split across products.
-Boxplot – Sales Distribution by Product
-Detects outliers and shows variability in sales for each product.

#  Sample Output
Bar Chart – Total Sales by Product
- Highlights which products perform best in total sales.

Line Chart – Monthly Sales Trend
- Shows seasonal changes in sales over the year.

Pie Chart – Product Sales Share
- Displays percentage sales contribution per product.

Boxplot – Sales Distribution
- Shows the spread and outliers in product sales.

# Deliverables
-task5_sales_analysis.ipynb – Google Colab containing the code.

-sales_data_50.csv – Dataset 

README.md – Project documentation (this file).

