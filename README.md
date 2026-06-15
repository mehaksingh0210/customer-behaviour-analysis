# internspark-task1
# Customer Behavior Analysis

## Project Overview

This project was completed as part of the **InternSpark Summer Internship (Data Analytics Domain)**. The objective was to analyze customer transaction data, identify customer segments, study purchasing patterns, evaluate customer retention trends, and provide business recommendations for improving customer engagement.

Using data analytics and machine learning techniques, customers were segmented into meaningful groups based on their purchasing behavior. The project also includes churn analysis and actionable recommendations to support data-driven decision making.

---

## Objectives

* Perform data cleaning and preprocessing
* Conduct feature engineering
* Segment customers using K-Means Clustering
* Profile each customer segment
* Analyze purchase patterns and customer behavior
* Evaluate customer retention and churn trends
* Provide actionable business recommendations

---

## Dataset Information

The dataset contains customer transaction records including:

* Customer ID
* Purchase Date
* Product Category
* Product Price
* Quantity
* Total Purchase Amount
* Payment Method
* Customer Age
* Returns
* Gender
* Churn Status

---

## Technologies Used

* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* K-Means Clustering

---

## Data Cleaning

The dataset was examined for data quality issues.

### Results

* No missing values found
* No duplicate records found
* Dataset was clean and ready for analysis

---

## Feature Engineering

The following features were created:

### Average Order Value

Calculated using:

Average Order Value = Total Purchase Amount / Quantity

### Purchase Month

Extracted from purchase date to analyze monthly trends.

### Purchase Year

Extracted from purchase date for temporal analysis.

---

## Customer Segmentation

Customer segmentation was performed using **K-Means Clustering** based on:

* Total Purchase Amount
* Quantity Purchased
* Age

Five customer segments were identified.

### Segment Profiles

| Segment                     | Description                                   |
| --------------------------- | --------------------------------------------- |
| Premium Customers           | Highest spending and purchasing frequency     |
| Mature High-Value Customers | Consistent high-value customers               |
| Young Frequent Buyers       | Young customers with strong purchase activity |
| Young Budget Customers      | Price-sensitive customers                     |
| Low Engagement Customers    | Lowest spending and engagement levels         |

---

## Key Findings

* Five distinct customer segments were identified.
* Premium Customers generated the highest revenue.
* Young Frequent Buyers showed strong growth potential.
* Approximately 20% of customers had churned.
* Customer behavior varied significantly across age groups and purchasing patterns.

---

## Churn Analysis

Customer retention analysis revealed:

* Retained Customers: 161,874
* Churned Customers: 40,744
* Churn Rate: 20.1%

These findings highlight the importance of targeted customer retention strategies.

---

## Business Recommendations

### 1. Launch a VIP Loyalty Program

Reward high-value customers with exclusive benefits and offers.

### 2. Implement Customer Retention Campaigns

Target customers at risk of churn using personalized promotions.

### 3. Strengthen Social Media Marketing

Focus on engaging young customer segments through digital campaigns.

### 4. Introduce Bundled Discounts

Encourage budget-conscious customers to increase purchase value.

### 5. Re-Engage Low Engagement Customers

Provide incentives and personalized recommendations to reactivate inactive customers.

---

## Project Deliverables

* Google Colab Notebook
* Data Visualizations
* Customer Segmentation Analysis
* Churn Analysis
* PDF Report
* GitHub Repository

---

## Results

The project successfully identified meaningful customer segments, purchasing trends, and retention patterns. The insights generated can help businesses improve customer engagement, optimize marketing strategies, and enhance long-term customer retention.

---

## Author

**Mehak Singh**

B.Tech CSE (AI & ML)

Data Analytics Intern – InternSpark Summer Internship

---

## Acknowledgements

* InternSpark Summer Internship Program
* Kaggle Dataset Provider
* Python Open Source Community
