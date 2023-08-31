# Customer Segmentation Using K-Means Clustering


This project focuses on customer segmentation using the K-means clustering algorithm. The goal is to group customers into distinct classes based on their attributes and behaviors, focusing on identifying those likely to subscribe to a bank term deposit.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Data Preprocessing](#data-preprocessing)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [K-Means Clustering](#k-means-clustering)
- [Model Evaluation](#model-evaluation)
- [Conclusion](#conclusion)

## Introduction

In the domain of direct marketing campaigns for a Portuguese banking institution, this project aims to uncover insights through customer segmentation. The primary objective is to employ the K-means clustering algorithm to categorize customers into meaningful groups, enabling more targeted marketing strategies.

## Dataset

The dataset used in this project originates from direct marketing campaigns and contains a variety of customer attributes such as age, job type, marital status, contact methods, and more. It also includes the crucial outcome variable - whether or not the customer subscribed to a bank term deposit.

## Data Preprocessing

Data preprocessing involved handling missing values, encoding categorical variables, and addressing outliers. Negative account balances were treated as overdraft situations based on established guidelines.

## Exploratory Data Analysis (EDA)

EDA delved into the distribution and relationships of variables. Histograms, scatter plots, and box plots were utilized to visualize the data's characteristics and uncover patterns. Insights were gained into customer age groups, job distributions, account balances, and more.

## K-Means Clustering

K-means clustering was applied to segment customers into two main classes: those who subscribe to a bank term deposit and those who decline. The process involved building a baseline model and selecting relevant features using the variance threshold technique. After encoding categorical variables, the model was evaluated based on precision, recall, F1-score, and accuracy.

## Model Evaluation

The classification report highlighted the model's performance in identifying potential and non-buyers. Precision, recall, and F1 scores were analyzed for both classes. Suggestions for model improvement were provided, including feature engineering, addressing class imbalance, and exploring advanced algorithms.

## Conclusion

In conclusion, this project demonstrated the power of K-means clustering in customer segmentation. While the baseline model showed promising insights, there is room for enhancement to create a more accurate and balanced classification system. The insights gained from this analysis can guide future marketing strategies to target potential customers effectively.

For a detailed walkthrough of the project code and findings, please refer to the [Jupyter Notebook](Customer Segmentation Using Kmeans Clustering.ipynb).

---

Feel free to contribute, fork, or provide feedback for this project. If you find it helpful, consider giving it a ⭐️!
