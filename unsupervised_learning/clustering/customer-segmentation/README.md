# Customer Segmentation using KMeans Clustering

This project performs **unsupervised machine learning** on a credit card customer dataset using **KMeans clustering** and **PCA (Principal Component Analysis)**. The goal is to segment customers into distinct groups based on their financial behavior for better understanding, targeting, and insights.

---

## 📌 Objective

The purpose of this project is to:

- Discover natural clusters in credit card customer behavior.
- Analyze patterns such as spending, payment habits, and cash advance usage.
- Help businesses understand different customer profiles for marketing, credit assessment, and rewards strategy.


---

## 📊 Dataset

**Dataset:** [Credit Card Customer Dataset](https://www.kaggle.com/datasets/youssefelbadry10/cc-general)  
**Source:** Kaggle  
**License:** Open for educational and non-commercial use  

This dataset contains anonymized credit card usage data, including:

- `BALANCE`, `PURCHASES`, `PAYMENTS`
- Frequency of transactions and cash advances
- Percentage of full payments and customer tenure

---

## 🛠 Methods Used

- Data Cleaning & Null Value Handling
- Feature Normalization (`StandardScaler` + `normalize`)
- Dimensionality Reduction with **PCA**
- **KMeans Clustering** with Elbow Method to determine optimal clusters
- Cluster visualization with decision boundaries and centroids
- Interpretation of clusters based on financial behavior

---

## 🔍 Key Results

After applying PCA and clustering:

- **4 customer segments** were identified
- Cluster behaviors included:
  - Disciplined spenders
  - High-value loyal customers
  - Cash-advance heavy users (risk-prone)
  - Installment-based planners

These insights can support **targeted marketing**, **risk evaluation**, and **customer retention strategies**.

---

## Visual Example

> PCA-reduced visualization with KMeans clusters and decision boundaries  
> (see the notebook for the full interactive version)

---

##  Tools & Libraries

- Python
- NumPy, Pandas
- Scikit-learn (PCA, KMeans)
- Matplotlib, Seaborn



