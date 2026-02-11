#  Sales Performance Analytics Dashboard

#  Project Overview

This project analyzes historical sales data to uncover patterns driving revenue, profit, and seasonal trends. The analysis transforms raw transactional data into actionable insights that support pricing, promotions, and market expansion strategies.

#  Business Problem

The company seeks to understand its sales performance across products, channels, and regions in order to improve profitability, reduce concentration risk, and support sustainable growth. Management observed variations in revenue and profit and changing demand patterns, highlighting the need to identify key revenue and profit drivers, detect anomalies, and optimize business strategies.

#  Objective

Provide business stakeholders with actionable insights into sales performance, revenue and profit drivers, seasonal trends, and pricing or margin risks to support data-driven decision making and sustainable growth.

#  Scope

Focus Area: Sales Performance and Revenue Analytics

#  Dashboard Preview

Dashboard file available in the powerbi folder.

#  Key Metrics (KPIs)

Monthly Sales Trend Over Time

Top 10 Products by Revenue

Top 10 Products by Average Profit Margin

Sales by Channel

Total Sales by State

Total Sales by US Region

Average Order Value AOV Distribution

Top and Bottom 10 Customers by Revenue

Top State Performance Revenue vs Orders


#  Data Preparation & Modeling

Data preparation and exploratory analysis were performed using Python. The analysis notebook is located in the python folder.

Cleaned and transformed raw sales data to ensure accuracy and consistency

Handled missing budgets and corrected data types

Structured data to support analysis and dashboard development

Performed exploratory data analysis to identify trends correlations and customer product segments

The original dataset used for analysis is stored in the data folder.


#  Data Analysis

All analysis was performed in Python using exploratory and statistical techniques. The notebook includes:

Univariate and bivariate analysis of revenue margin unit price and product channel region breakdowns

Trend and seasonality analysis highlighting recurring surges and dips

Outlier detection of extreme transactions in revenue and unit price

Correlation and segmentation analysis clustering customers by revenue versus profit margin


#  Visualization & Insights

An interactive Power BI dashboard was developed to present key trends and performance indicators. The dashboard file is located in the powerbi folder.

Visualized revenue and profit trends across products channels and regions

Enabled stakeholders to explore seasonal trends and anomalies

Highlighted top performing products regions and channels for decision support

Supported data driven pricing promotion and expansion strategies


#  Tools & Technology

Python Data Cleaning and Exploratory Data Analysis

Power BI Data Modeling DAX Calculations Interactive Reporting

Data Model Type Star Schema


#  Project Structure

```
sales-performance-analytics/
 ├── README.md
 ├── data/
 │   ├── regional_sales_dataset.csv
 │   └── sales_data.csv
 ├── python/
 │   └── EDA_Regional_Sales_Analysis.ipynb
 ├── powerbi/
 │   └── Sales_Report.pbix
 └── documentation/
     ├── Business_Problem_Document.pdf
     └── Regional_Sales_Analysis.pptx

 ```    

#  Insights & Narrative

Pronounced Seasonality: January revenues average $124M, dipping to $95M in April.

SKU Concentration: Products 26 and 25 together drive approximately 25 percent of total sales.

Channel Trade Off: Wholesale captures 54 percent of volume while Export delivers the highest average margin at approximately 38 percent.

Geographic Dominance: California records about 7.6K orders and $230M revenue while the West region shows the largest performance swings.

Top Customers: Aibox Company and State Ltd generate the highest revenue contribution.


#  Recommendations

Seasonal Promotions: Launch recovery campaigns in April and amplify January offers to smooth revenue swings.

SKU Optimization: Focus on top products 26 and 25 and re evaluate pricing or phase out low margin SKUs.

Channel Expansion: Incentivize Export partnerships for higher margins and introduce volume deals in Wholesale.

Regional Investment: Replicate California success in other regions and increase marketing in the Northeast and Midwest.

Margin Monitoring: Flag orders below 80 percent margin and analyze cost drivers to improve underperforming segments.
