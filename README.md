# Customer Segmentation Using KMeans Clustering

## Overview
This project performs customer segmentation using KMeans clustering on structured financial data. The goal is to identify meaningful customer groups based on financial characteristics such as age, income, credit score, loan amount, and investment. These insights can help financial institutions personalize offerings and improve decision-making.

## Dataset
- **Rows:** 1,000 customers
- **Columns:** 
  - `Customer_Age`
  - `Annual_Income`
  - `Credit_Score`
  - `Loan_Amount`
  - `Investment`

## Objective
Group customers into distinct segments to uncover patterns in financial behavior for targeted marketing, credit planning, or investment strategy.

## Methodology
1. **Data Preprocessing**:
   - Standardized numeric features using `StandardScaler`.

2. **Exploratory Data Analysis (EDA)**:
   - Visualized feature distributions and relationships.
   - Used correlation heatmaps for initial insights.

3. **Clustering**:
   - Applied the Elbow Method to determine optimal clusters (k=4).
   - Implemented KMeans clustering to assign each customer to a segment.

4. **Cluster Analysis**:
   - Interpreted segment characteristics using group-wise averages.
   - Labeled customer groups with business-friendly names (e.g., *Young Wealth Builders*, *Affluent Mid-Age Investors*).

## Key Results
- Identified 4 distinct customer segments:
  - Varying in income, credit score, and investment behavior.
  - Insights support tailored financial product offerings.

## Tools Used
- Python
- Pandas
- Scikit-learn
- Matplotlib & Seaborn

## Sample Output
| Cluster | Avg Income | Avg Credit Score | Avg Investment | Description |
|---------|------------|------------------|----------------|-------------|
| 0       | ₹1.18L     | 503              | ₹25K           | Affluent Mid-Age Investors |
| 1       | ₹82K       | 560              | ₹12K           | High Loan Seekers |
| 2       | ₹47K       | 597              | ₹25K           | Frugal Investors |
| 3       | ₹86K       | 648              | ₹39K           | Young Wealth Builders |


## Author
Gaurav Mishra  
MBA (Finance) Candidate | CMS Business School, Jain University

