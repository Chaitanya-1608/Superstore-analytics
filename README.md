# Superstore Analytics

## Table of Contents

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Key insights](#Key-insights)
- [Recommendations](#recommendations)

### Project Overview
---

This data analysis project aims to provide insights into the performance of superstore over the past four years. By analyzing various aspects of the orders data, we seek to identify trends, make data-driven recommendations, and gain a deeper understanding of the its performance.

### Data Sources 
Both orders data and returns data is taken from Kaggle.
 - [See here](https://www.kaggle.com/datasets/aditirai2607/super-market-dataset)


### Tools

- Pandas - EDA
- Matplotlib - Data visualisation
- Sklearn - Cluster analysis

### Data Cleaning/Preparation

In the initial data preparation phase, we performed the following tasks:
1. Data loading and inspection.
2. Data cleaning and formatting.
3. Adding key matrices required for analysis

### Exploratory Data Analysis

EDA involved exploring the data to answer key questions, such as:

- Categorywise and sub category wise total sales
- Constrywise region wise total sales
- Yearwise monthwise total sales
- Cities contributing to 80% of sales
- Profitable categories across regions
- Most profitable region and category
- Top selling sub categories
- Sub categories which have achieved overall margins greater than 30%
- Sub category wise top and bottom region in terms of sales
- Most and least preferred Shipmode among all the sub categories
- Shipmodewise average processing time
- Average order value
- Sub categorywise average processing time
- First and latest order date for each category
- Sub categories where average profit is more that half of the max profit in that sub category
- top 5 sub categories in west region by total quantity sold
- order ids where there is only 1 product bought by the customer
- product id and total sales of highest selling products (by no of units sold) in each category
- top 3 and bottom 3 products by sales in each region\
- Among all the sub categories..which sub category had highest month over month growth by sales in Jan 2022
- top 3 products in each category by year over year sales growth in year 2024
- top 3 products in each category by highest rolling 3 months total sales for Jan 2020
- products were returned more than 20 times
- Category wise sales of orders that were not returned

### Customer segmentation

Region wise customer segmentation was done based on sales, quantity purchased, or profitability. The same can be used for personalized marketing, targeted advertising, and improved customer retention strategies.


### Key insights

The analysis results are summarized in the attached document.


### Recommendations

- Identify Top Categories/Sub-Categories: Products like Technology and Office Supplies often drive higher sales      or profit margins.
- Expand Product Range: Increase the variety of top-performing sub-categories.
- Regional Promotions: As its seen that Central region is underperforming, offer targeted discounts or bundles       for top performing products to boost sales further.
- Return reason to be captured: There is a need to capture the return reason to 
  understand the real problem behind returns.
- Average order value: AOV can be targeted to bring to 300 $.
- There are only 10 states out of 59 which are contributing to orders, so the order states 
  shall be targeted to improve sales.

### Limitations

Customer segmentation can be done with more holistics approach by incorporating purchasing behavior, demographics, preferences based on categories and sub categories.

