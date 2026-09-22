# Superstore Sales Analysis

A data analysis project using Python and Power BI to explore Superstore sales data, understand business performance, and identify patterns in sales, profit, products, customers, categories, regions, and other business areas.

## Project Objective

The main objective of this project is to analyze Superstore sales data and understand overall business performance.

The analysis focuses on:

- Sales and profit performance
- Order and quantity trends
- Category and sub-category performance
- Regional and segment-wise performance
- Product-level performance
- Customer performance
- Yearly, quarterly, and monthly sales trends
- Discount and profit relationship
- Shipping mode performance
- Creating an interactive Power BI dashboard

## Dataset

The project uses a Superstore sales dataset containing information about:

- Orders
- Customers
- Products
- Categories and sub-categories
- Sales
- Profit
- Quantity
- Discount
- Regions
- Segments
- Shipping modes
- Order and shipping dates

The dataset contains **10,194 rows and 21 columns**.

The dataset covers orders from **2023 to 2026**.

## Tools and Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook
- Power BI
- GitHub

## Data Cleaning

The dataset was checked before performing the analysis.

The following checks were performed:

- Checked the number of rows and columns
- Checked column names and data types
- Checked for missing values
- Checked for exact duplicate rows
- Checked categorical values for consistency
- Converted the `Order Date` column into datetime format
- Checked duplicate Order IDs

Duplicate Order IDs were not removed because a single order can contain multiple products or line items.

Negative profit values were also retained because they can represent orders where the business made a loss.

## Feature Engineering

New columns were created to make the analysis easier:

- `Year`
- `Month`
- `Month Name`
- `Quarter`
- `Profit Margin`

The `Profit Margin` was calculated using:

`Profit / Sales × 100`

These additional columns were used for time-based and profitability analysis.

## Analysis Performed

The following analyses were completed in Python.

### 1. Overall KPI Analysis

Calculated:

- Total Sales
- Total Profit
- Total Orders
- Total Quantity Sold
- Overall Profit Margin

### 2. Monthly Sales Analysis

Monthly sales were analyzed to understand sales trends over time.

### 3. Yearly Performance Analysis

Sales and profit were compared across different years, including yearly sales growth.

### 4. Quarterly Performance Analysis

Sales and profit were analyzed quarter-wise to understand changes throughout each year.

### 5. Product Analysis

Products were analyzed based on:

- Sales
- Profit
- Lowest-profit products

### 6. Category Analysis

Sales, profit, quantity, and profit margin were compared across different product categories.

### 7. Region Analysis

Regional performance was analyzed using:

- Sales
- Profit
- Quantity
- Orders
- Profit Margin

### 8. Segment Analysis

Sales, profit, quantity, orders, and profit margin were analyzed for different customer segments.

### 9. Sub-Category Analysis

Sub-categories were compared based on sales, profit, quantity, and orders.

### 10. Category-Year Analysis

Category performance was compared across different years to understand changes in sales and profit over time.

### 11. Discount and Profit Analysis

The relationship between discount and profit was explored using grouped analysis, scatter plots, and correlation.

### 12. Quantity Analysis

Quantity was compared with sales and profit to understand the relationship between the number of items sold and business performance.

### 13. Customer Analysis

Customers were analyzed based on:

- Total Sales
- Total Profit
- Total Quantity
- Total Orders
- Profit Margin

Top customers by sales and profit were also identified.

### 14. Ship Mode Analysis

Different shipping modes were compared using sales, profit, quantity, orders, and profit margin.

## Key Findings

Some of the main findings from the analysis were:

- Total sales were approximately **2.33 million**.
- Total profit was approximately **292.30K**.
- The dataset contained **5,111 unique orders**.
- Total quantity sold was **38,654**.
- Overall profit margin was approximately **12.56%**.
- Sales increased strongly in the later years of the dataset.
- Product, category, region, segment, and sub-category performance showed differences in both sales and profitability.
- Some products generated relatively high sales but comparatively lower profit.
- Discount and profit were analyzed to understand their relationship.
- Regional and category-level analysis helped identify differences in business performance.

## Power BI Dashboard

As part of the project, an interactive **Sales Performance Dashboard** was created using Power BI.

The dashboard includes:

- Total Sales
- Total Profit
- Total Orders
- Total Quantity Sold
- Sales by Order Date
- Sales by Category
- Profit by Category
- Sales by Region
- Sales by Segment
- Sales by Sub-Category
- Sales vs Profit by Region
- Quantity Sold by Category
- Sales by Ship Mode

The **Sales by Order Date** visual can be used to understand sales trends across different time periods using the Order Date hierarchy.

The dashboard also includes slicers for:

- Year
- Region

These slicers allow the dashboard to be explored interactively.

## Project Files

```text
Superstore-Sales-Analysis/
│
├── Superstore Dataset.csv
├── Superstore Dataset.ipynb
├── Sales_Performance_Dashboard.pbix
└── README.md
```
## Thank you for taking the time to explore this project.

I hope this project gives a clear overview of my learning and practical experience in data analysis using Python and Power BI.
