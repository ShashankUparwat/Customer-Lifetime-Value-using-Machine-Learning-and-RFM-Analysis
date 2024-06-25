# Customer Lifetime Value using Machine Learning and RFM Analysis

## Project Overview

This project focuses on developing a sophisticated Customer Lifetime Value (CLV) model using Python. The model leverages data analytics to predict future revenue from customer segments, helping businesses identify high-value customers and optimize their marketing strategies. By enhancing long-term profitability and customer retention, this model serves as a crucial tool for data-driven decision-making. **The dataset used in this project was created using ChatGPT**, ensuring a diverse and comprehensive set of customer data.

## Dataset
1. retail_data.csv (_Created using ChatGPT_)

## Methodology

#### 1. Data Preprocessing:

- Loading and cleaning the retail_data dataset.
- Creating features such as Recency, Frequency, and Monetary value.

#### 2. Exploratory Data Analysis (EDA):

- Visualizing customer purchase behavior.
- Segmenting customers based on their RFM values.

#### 3. Clustering Analysis:

- Applying K-Means clustering to identify distinct customer segments.
- Visualizing the clusters and interpreting their characteristics.

#### 4. Machine Learning Modeling:

- Building a Regression model to predict _how much amount is customer going to spend in the future_.
- Building a Classification model to _predict to preddict the probability of customer purchasing in the future_.
- Validating the model's accuracy and performance.

#### 5. Results
- The CLV model successfully identifies high-value customer segments and predicts future revenue, providing actionable insights for optimizing marketing strategies, customer retaintion, and enhancing long-term profitability.

##### Clustering Analysis Results

1. Customer Engagement:
- Cluster 1: Since customers in this cluster have a high spend but no activity in the last 90 days, they might require re-engagement strategies such as targeted promotions or personalized offers to reactivate them.
  
2. High-Value Customers:
- Cluster 2 and Cluster 3: These clusters contain high-value customers who are very active. Focus on retaining these customers with loyalty programs, exclusive deals, and excellent customer service.
  
3. Recently Active Customers:
Cluster 0: Customers in this cluster are relatively recent and active. Continue engaging them with regular communications and promotions to maintain their activity levels.
