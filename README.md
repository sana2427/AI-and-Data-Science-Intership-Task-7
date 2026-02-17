# Task 2: Customer Segmentation Using Unsupervised Learning

## Overview
This repository contains the solution for **Task 2: Customer Segmentation Using Unsupervised Learning**, completed as part of my AI & Data Science Internship tasks.

---

## Objective
The objective of this task is to group customers based on their spending behavior using clustering techniques.  
The task focuses on discovering hidden patterns in customer data and designing marketing strategies for each identified segment.

---

## Dataset
**Dataset Name:** Mall Customers Dataset  
**Type:** Structured CSV dataset  

---

## Dataset Description
**Total Records:** 200  

**Features:**
- CustomerID  
- Gender  
- Age  
- Annual Income (k$)  
- Spending Score (1–100)  

The Spending Score represents how much a customer spends at the mall.  
This dataset is commonly used for customer segmentation and clustering problems.

---

## Tools & Technologies Used
- Python  
- NumPy  
- pandas  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- Jupyter Notebook / Google Colab  

---

## Approach

### 1️⃣ Data Loading
- Loaded the dataset using `pandas.read_csv()`  
- Converted it into a DataFrame for analysis  

### 2️⃣ Data Preprocessing
- Converted categorical Gender values into numeric format  
- Removed CustomerID since it does not affect behavior analysis  
- Applied StandardScaler to normalize features  

### 3️⃣ Exploratory Data Analysis (EDA)
- Analyzed distributions of Age, Income, and Spending Score  
- Observed natural group patterns between income and spending behavior  
- Identified that spending is not always dependent on income  

### 4️⃣ Finding Optimal Clusters
- Used the Elbow Method to calculate WCSS  
- Determined the optimal number of clusters as **5**  

### 5️⃣ K-Means Clustering
- Applied K-Means algorithm  
- Segmented customers into 5 groups  

### 6️⃣ Dimensionality Reduction & Visualization
- Used PCA for 2D visualization  
- Used t-SNE for better cluster separation visualization  

### 7️⃣ Cluster Analysis
- Calculated average feature values for each cluster  
- Identified premium, average, and price-sensitive customers  

### 8️⃣ Strategy Development
- Designed targeted marketing strategies for each customer segment  

---

## Results & Insights
- Customers were divided into five meaningful groups  
- Spending behavior is not directly dependent on income  
- Segmentation helps improve marketing efficiency and profitability  

---

## Conclusion
This task demonstrates how unsupervised learning can be used for customer segmentation.  
K-Means successfully identified meaningful customer groups, and visualization techniques confirmed clear cluster separation.  
Data-driven strategies can significantly improve business performance.

---

## Skills Gained
- Unsupervised Learning (K-Means)  
- Dimensionality Reduction (PCA & t-SNE)  
- Customer Segmentation  
- Exploratory Data Analysis (EDA)  
- Strategy Development  
