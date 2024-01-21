# CustomerSegmentation_RFM
Performed precise RFM Analysis of insightful information about consumer behavior, purchase trends, and satisfaction for targeted marketing and retention strategies. The project is to perform RFM analysis on the E-commerce dataset, segmenting customers into distinct groups based on their RFM scores. These segments will serve as valuable indicators for refining marketing strategies and improving customer retention efforts.

Dataset - The dataset consists of 541,909 records spread across 8 columns.
https://www.kaggle.com/datasets/carrie1/ecommerce-data

## 1 Data Preprocessing
Imported the dataset and performed necessary data preprocessing steps, including data cleaning, handling missing values, and converting data types if needed.

## 2 RFM Calculation
Calculated the RFM metrics for each customer:
Recency (R): How recently a customer made a purchase. Calculated the number of days since the customer's last purchase.
Frequency (F): How often a customer makes a purchase. Calculated the total number of orders for each customer.
Monetary (M): The total monetary value of a customer's purchases. Calculated the sum of the total price for each customer.

## 3 RFM Segmentation
Assigned RFM scores to each customer based on their quartiles for each RFM metric.
Combined the RFM scores to create a single RFM score for each customer.

## 4 Customer Segmentation
Used clustering techniques to segment customers based on their RFM scores. Experimented with different numbers of clusters to find the optimal number that provides meaningful segments.

## 5 Segment Profiling
Analyzed and profiled each customer segment describing the characteristics of customers in each segment, including their RFM scores and any other relevant attributes.

## 6 Marketing Recommendations
Provided actionable marketing recommendations for each customer segment. How can the business tailor its marketing strategies for each group to improve customer
retention and maximize revenue?

