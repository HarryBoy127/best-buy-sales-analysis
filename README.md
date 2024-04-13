# best-buy-sales-analysis

1. Introduction

In this report, we aim to analyze sales data using Python to derive insights and answer key business questions. The dataset used for this analysis contains approximately 12 months of sales data for electronic devices, including information such as purchase dates, product types, and sales revenue.

2. Data

The dataset used in this project consists of sales data spanning over 12 months. It contains thousands of records of electronic devices purchased, categorized by month and product type.

3. Methods

The primary objective of this project is to analyze the sales data using Python and provide actionable insights to support decision-making processes.

4. Data Cleaning

Before proceeding with the analysis, the dataset underwent a cleaning process, which involved removing any missing values (NAN) from the dataframe and converting columns such as "Months" and "OrderDate" to the appropriate data types.

5. Data Exploration and Business Questions

Following data cleaning, we delved into exploring the dataset to answer several key business questions:

i) Best Month for Sales: We analyzed the sales data to determine the best-performing month in terms of revenue generated.

ii) City with Highest Sales: Identifying the city that sold the most products to understand regional sales patterns.

iii) Optimal Time for Advertisements: Analyzing sales data to identify the best times to display advertisements, maximizing the likelihood of customer purchases.

iv) Products Frequently Sold Together: Exploring product combinations frequently purchased together to inform cross-selling strategies.

v) Top-Selling Product and Reasons: Identifying the product that sold the most and providing insights into the factors contributing to its success.

6. Analysis Techniques

To address these business questions, various Python libraries and techniques were employed:

Concatenating multiple CSV files to create a unified DataFrame using pd.concat.
Adding necessary columns and parsing cells as strings to extract relevant information.
Utilizing the .apply() method for efficient data manipulation.
Employing groupby to perform aggregate analysis and derive insights.
Visualizing results through bar charts and line graphs using matplotlib.
Labeling graphs to enhance readability and understanding.

7. Conclusion

Through the analysis conducted using Python, we were able to gain valuable insights into sales performance, regional trends, optimal advertising times, and product relationships. These insights can be utilized by decision-makers to enhance sales strategies, optimize advertising campaigns, and drive overall business growth.

In conclusion, leveraging Python for sales analysis proved to be an effective approach in extracting actionable insights from the dataset, ultimately enabling informed decision-making processes.