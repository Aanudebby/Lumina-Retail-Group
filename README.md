# Introduction
The Lumina Sales Report project provides an end-to-end analysis of sales performance across products, regions, and customer segments.
Lumina Retail Group is a fast-growing retail brand operating physical stores and an e-commerce platform, offering a wide range of products from electronics to groceries.
With rapid expansion and a growing customer base, Lumina has collected large volumes of transactional data.
This project leverages Power BI to transform that data into actionable insights, helping the leadership team improve inventory planning, understand customer behavior, and drive revenue growth.<br>

 ## Problem Statement
Lumina faced challenges in understanding:
- Which products drive the most revenue.
- How sales performance varies by region and customer demographics.
- Which customer segments are most profitable.
- Trends in sales volume and revenue growth over time.
  
## Data Sourcing
The dataset includes transactional sales records collected over a defined period and contains:

- Product Information: Category, product name, unit price.
- Sales Data: Quantity sold, total revenue, discounts applied.
- Customer Data: Region, segment, demographics.
- Time Dimension: Order date, year, month, quarter.

<img width="1320" height="433" alt="image" src="https://github.com/user-attachments/assets/eaa798c6-7e8c-4ea6-8b46-36df12c439dc" />

# Data Modelling

A Star Schema was developed in Power BI, consisting of:

Fact Table:which contains all the ID's.

Dimension Tables which contain the: Customers Dim, Products Table, Store Dim, and Date Dim. 
Key DAX measures and calculated columns created include:
Total Revenue

Total Quantity Sold

Average Order Value (AOV)

Sales by Region & Product Category

Year-over-Year (YoY) Growth
<img width="830" height="495" alt="image" src="https://github.com/user-attachments/assets/b8ecce58-b4ae-456a-afb3-ee38ca88b134" />

Data Cleaning & Transformation

The dataset was generally clean and required minimal transformation. The key adjustment made was:

Date Formatting: The Order Date column was imported as text and had to be converted into a proper date data type. This step was crucial to enable accurate time-based analysis (monthly, quarterly, and yearly trends) in Power BI.

No significant missing values, duplicates, or categorical inconsistencies were detected, so the dataset was ready for modeling after the date correction.

<img width="1337" height="433" alt="image" src="https://github.com/user-attachments/assets/55317d00-32a3-4b9d-a3b1-3930ceadbfba" />

# Insights

Key findings from the analysis include:

Top Products: A small percentage of products generated the majority of sales revenue.

Regional Performance: Certain locations consistently outperformed others in terms of revenue and volume.

Customer Segmentation: High-value customers showed distinct purchasing patterns that can be targeted.

Seasonality: Sales spiked during specific months/quarters, suggesting strong seasonal trends.

# Recommendations

Based on insights, Lumina Retail group can:

Focus on high-performing products with more marketing and distribution.

Develop region-specific sales campaigns for underperforming areas.

Implement loyalty programs to retain high-value customers.

Plan seasonal promotions and inventory ahead of peak sales periods.

Encourage upselling & cross-selling to increase AOV.

 # Dashboard  
[Lumina Sales Dashboard Preview]<br>
<img width="734" height="550" alt="image" src="https://github.com/user-attachments/assets/b1d4bb58-b966-4959-b663-b7b474e82b47" />

 [Click here to view the Interactive Dashboard](https://app.powerbi.com/view?r=eyJrIjoiYTAxNDI5MGUtNmZhNC00MThkLWEwMzgtZGEwNTMzZmYyYWZkIiwidCI6ImI3ZmE1MTQ0LTY0YzUtNDllZS1hMmU1LTBjYmYzNmQ2OTQ3OCIsImMiOjh9)


# Tools & Technologies

Power BI – Data visualization, modeling, and reporting.

Power Query – Data cleaning and transformation.

DAX – Calculated measures and KPIs.

Excel – Initial data exploration and preprocessing.
