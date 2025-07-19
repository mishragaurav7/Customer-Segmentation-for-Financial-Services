# Customer Segmentation Using KMeans Clustering

## 📌 Project Overview
This project focuses on identifying distinct customer segments based on financial behavior using KMeans clustering. By analyzing structured data such as age, income, credit score, loan amount, and investment value, the project aims to uncover patterns that can inform personalized financial services, targeted marketing, and strategic decision-making.

----

## 📂 Dataset Summary
- **Total Records:** 1,000 customers
- **Features:**
  - `Customer_Age`: Age of the customer
  - `Annual_Income`: Yearly income (in ₹)
  - `Credit_Score`: Creditworthiness rating
  - `Loan_Amount`: Amount of active loans
  - `Investment`: Value of investments made

----

## 🎯 Objective
Segment customers into meaningful groups based on financial indicators to better understand their behavior and preferences.

----

## ⚙️ Steps Performed

### 1. Data Preprocessing
- Cleaned and standardized the dataset using `StandardScaler` to ensure equal weighting across features.

### 2. Exploratory Data Analysis (EDA)
- Visualized distributions of age, income, credit score, loan, and investment using histograms.
<img width="421" height="290" alt="Distribution_of_customer_features" src="https://github.com/user-attachments/assets/076b989e-9b1e-4584-8d8b-ec62ece3a5f6" />

- Used correlation heatmaps to understand feature relationships.
<img width="365" height="311" alt="Feature_correlation_heatmap" src="https://github.com/user-attachments/assets/5e33ce0d-5cb6-46dd-a834-b19ddfc84b7e" />


### 3. Optimal Cluster Selection
- Applied the **Elbow Method** to determine the best number of clusters.
<img width="283" height="172" alt="Optimal_clusters" src="https://github.com/user-attachments/assets/97a6fd16-f3df-4aea-b471-61fb4ed0634b" />

- Found optimal `k = 4`.

### 4. KMeans Clustering
- Used `KMeans` algorithm to assign each customer to one of the four clusters based on feature similarity.
<img width="412" height="397" alt="Customer_clusters" src="https://github.com/user-attachments/assets/dc320e29-abb3-4800-8e04-43630a59fccb" />


### 5. Cluster Interpretation
- Calculated average values within each cluster to interpret segment characteristics.
- Labeled each group based on financial behavior patterns.

----

## 📊 Cluster Insights

| Cluster | Avg Age | Avg Income | Avg Credit Score | Avg Loan | Avg Investment | Label |
|---------|---------|------------|------------------|----------|----------------|-------|
| 0       | 47.7    | ₹1.18L     | 503              | ₹14K     | ₹25K           | Affluent Mid-Age Investors |
| 1       | 46.0    | ₹82K       | 560              | ₹37K     | ₹12K           | High Loan Seekers |
| 2       | 41.5    | ₹47K       | 597              | ₹13K     | ₹25K           | Frugal Investors |
| 3       | 39.5    | ₹86K       | 648              | ₹33K     | ₹39K           | Young Wealth Builders |

----
## 🧰 Tools & Technologies
- Python
- Pandas, NumPy
- Scikit-learn (StandardScaler, KMeans)
- Matplotlib, Seaborn

----

## ✅ Outcomes
- Successfully segmented 1,000 customers into four data-driven, interpretable groups.
- Generated actionable insights that can support financial institutions in personalizing loan, credit, and investment products.

----

## 🚀 How to Use
1. Clone the repository or download the notebook.
2. Install required libraries using `pip install -r requirements.txt` (optional).
3. Run the Jupyter notebook step-by-step to reproduce results.

----

## 👤 Contact
**Gaurav Mishra**  
Email: (7mishragaurav@gmail.com)
GitHub: (https://github.com/mishragaurav7)
LinkedIn: (www.linkedin.com/in/gaurav-mishra-3788ba271)

