# Customer Segmentation using K-Means Clustering

## 1. Introduction

Context:

This project focuses on customer segmentation, also known as market basket analysis, using unsupervised machine learning techniques. The primary goal is to segment customers based on their purchasing behavior and demographic details, enabling targeted marketing strategies.

Problem Statement:

As a supermarket mall owner, you want to identify potential target customers who can be easily converted for marketing efforts. This will help in creating effective marketing strategies to maximize revenue and customer retention.

## 2. Data Overview

The dataset consists of customer information obtained through membership cards, including:

Customer ID

Age

Gender

Annual Income

Spending Score (assigned based on customer behavior and purchasing data)

Data Preprocessing:

The dataset was loaded and checked for missing values.

Column names were standardized for ease of analysis.

Basic exploratory data analysis (EDA) was performed.

## 3. Exploratory Data Analysis (EDA)

Pairplot Analysis: A pairplot was generated to visualize relationships between Age, Annual Income, and Spending Score.

Scatter Plot (Annual Income vs. Spending Score): This plot helps to identify possible customer groups visually before applying clustering.

Summary Statistics: Descriptive statistics provided insights into the distribution of variables.

## 4. K-Means Clustering Approach

WCSS (Within-Cluster Sum of Squares) Calculation:

The optimal number of clusters was determined using the Elbow Method.

A range of clusters (1-10) was tested, and the WCSS values were plotted to identify the optimal cluster count.

K-Means Model Training:

The dataset was segmented into clusters based on Annual Income and Spending Score.

The cluster centroids were calculated and plotted for better visualization.

The final segmentation identified distinct groups based on spending behavior and income levels.

## 5. 3D Visualization of Customer Segments

A 3D scatter plot was created using:

Age (X-axis)

Annual Income (Y-axis)

Spending Score (Z-axis)

This helped in understanding the clusters better, allowing for more refined marketing decisions.

## 6. Key Findings & Insights

Customers can be segmented into different categories based on spending behavior and income.

The model successfully identifies high-value customers who should be prioritized for loyalty programs.

Low-income, high-spending customers may need different engagement strategies compared to high-income, high-spending customers.

## 7. Business Recommendations

Targeted Promotions: Different marketing strategies can be applied to different clusters.

Loyalty Programs: High-value customers should be rewarded to encourage repeat purchases.

Personalized Offers: Data-driven insights can help in crafting customer-specific promotions.

Customer Retention Strategies: Engagement methods for low-spending customers should be explored.

## 8. Conclusion

The customer segmentation model provides valuable insights into customer purchasing patterns. These insights can be leveraged for strategic decision-making, improving customer satisfaction, and increasing revenue.

