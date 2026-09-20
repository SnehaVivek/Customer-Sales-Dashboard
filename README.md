# Customer Sales Dashboard | Power BI

## Project Overview

Transformed raw customer sales data into an interactive **Power BI dashboard** to analyze sales performance across products, categories, regions, customers, and months.

The project involved preparing and cleaning the dataset in **Power Query**, building relationships between multiple Excel tables, and creating interactive visualizations and KPIs in Power BI to identify key sales trends and patterns.

## Tools & Technologies

- **Microsoft Excel** – Raw dataset and supporting data tables
- **Power Query** – Data cleaning and transformation
- **Power BI** – Data modeling, visualization, and dashboard development

## Dataset

The Excel workbook contains four main tables:

- **Sales** – Order ID, Order Date, Product ID, Customer ID, Region, Quantity, and Unit Price
- **Products** – Product ID, Product Name, and Category
- **Customers** – Customer ID, Customer Name, and Region
- **Calendar** – Date, Year, Month, Month Number, and Quarter

## Data Preparation

The raw Excel data was cleaned and prepared using **Power Query** before being loaded into Power BI.

Key data preparation steps included:

- Removed duplicate records
- Trimmed and cleaned text fields
- Standardized data values
- Checked data types and formatting
- Prepared date-related fields for analysis
- Loaded the refined datasets into Power BI
- Structured the data for dashboard analysis

## Dashboard Features

The dashboard provides an interactive view of:

### Key Performance Indicators
- Total Sales
- Total Quantity Sold
- Highest Sales Region
- Highest Sales Month
- Most Sold Product

### Sales Analysis
- Total Sales by Product
- Total Sales by Product Category
- Total Sales by Region
- Total Sales by Month and Region
- Total Sales by Month and Product Category
- Sales and Quantity trends over time
- Sales and Quantity by Product

### Customer Analysis
- Customer-level sales performance
- Sales contribution by customer
- Customer distribution across regions

## Key Insights

The dashboard enables users to identify:

- Products contributing the most to overall sales
- Product categories with higher sales volumes
- Regions generating higher sales
- Monthly changes in sales performance
- Products with higher quantities sold
- Customer-level sales contributions
- Relationships between sales value and quantity sold

## Dashboard Preview

![Customer Sales Dashboard](dashboard.png)

## Project Workflow

```text
Raw Excel Data
      ↓
Data Cleaning & Transformation
      ↓
Power Query
      ↓
Data Modeling
      ↓
Power BI Visualizations
      ↓
Interactive Sales Dashboard
