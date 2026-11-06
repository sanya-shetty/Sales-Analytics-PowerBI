 Sales Performance & Business Insights Dashboard

1. Project Overview

This project analyses sales performance using Power BI. The objective is to identify revenue trends, profitable product categories, top-performing products, customer segments and geographical sales patterns.

The dashboard provides interactive insights to support business decision-making.

Project Type:Data Analytics / Business Intelligence

Tool Used: Microsoft Power BI

Dataset: Synthetic sales dataset created for learning and portfolio development.

 2. Project Objectives

- Analyse overall revenue and profit.
- Calculate profit margins and average order value.
- Identify top-performing products.
- Compare revenue across product categories.
- Analyse state-wise sales performance.
- Understand customer segment performance.
- Identify monthly revenue trends.

3. Dataset Description

The project uses three CSV files:

| File | Description |
|---|---|
| Sales.csv | 500 sales transactions |
| Products.csv | 8 product records |
| Customers.csv | 100 customer records |

 4. Tools and Technologies

- Power BI Desktop
- Power Query
- DAX
- Data Modelling
- Data Visualization

5. Data Preparation

- Checked column names and data types.
- Inspected missing values and errors.
- Checked duplicate OrderIDs, ProductIDs and CustomerIDs.
- Verified the data before building relationships.

 6. Data Modelling

Created relationships between three tables:

- Products[ProductID] → Sales[ProductID]
- Customers[CustomerID] → Sales[CustomerID]

Both relationships use a one-to-many structure.
 7. DAX Measures

Created the following measures:

- Total Revenue
- Total Profit
- Total Quantity
- Profit Margin
- Average Order Value

 8. Key Business Insights

- Electronics generated the highest revenue.
- Electronics generated the highest total profit.
- Furniture had a higher profit margin than Electronics.
- Tamil Nadu was the highest-revenue state.
- Small Business was the highest-revenue customer segment.
- April recorded the highest monthly revenue.
- Laptop was the highest-revenue product.

 9. Dashboard Features

- Interactive State slicer.
- Interactive Category slicer.
- KPI cards.
- Revenue and profit analysis.
- Monthly revenue trend.
- Top 5 products analysis.
- Customer segment analysis.

 10. Conclusion

This project demonstrates how Power BI can transform raw sales data into meaningful business insights through data preparation, data modelling, DAX calculations and interactive visualizations.

The dataset is synthetic and was used strictly for educational and portfolio purposes.