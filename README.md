# Customer Segmentation using K-Means Clustering

## Project Overview
This project uses K-Means Clustering, an unsupervised machine learning algorithm, to segment mall customers based on their annual income and spending score. The goal is to identify different customer groups that can help businesses improve marketing strategies and customer targeting.

---

# Dataset
Dataset Used: `Mall_Customers.csv`

## Features
- CustomerID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1-100)

---

# Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

# Machine Learning Technique

## K-Means Clustering
K-Means groups customers into clusters based on similarities in spending behavior and income patterns.

---

# Steps Performed
1. Imported required libraries
2. Loaded and explored dataset
3. Selected important features
4. Applied feature scaling
5. Used Elbow Method to find optimal clusters
6. Trained K-Means model
7. Visualized customer segments
8. Analyzed cluster behavior

---

# Cluster Summary Table

| Cluster | Annual Income (k$) | Spending Score (1-100) | Age |
|---|---|---|---|
| 0 | 55.30 | 49.52 | 42.72 |
| 1 | 86.54 | 82.13 | 32.69 |
| 2 | 25.73 | 79.36 | 25.27 |
| 3 | 88.20 | 17.11 | 41.11 |
| 4 | 26.30 | 20.91 | 45.22 |

---

# Cluster Interpretation

## Cluster 0 — Average Customers
- Medium income
- Medium spending behavior
- Middle-aged customers

## Cluster 1 — Premium Customers
- High income
- High spending score
- Valuable target customers

## Cluster 2 — Young High Spenders
- Low income
- Very high spending
- Younger customers with impulsive buying behavior

## Cluster 3 — Careful Wealthy Customers
- High income
- Low spending score
- Customers with saving-focused behavior

## Cluster 4 — Low Value Customers
- Low income
- Low spending
- Less active customers

---

# Business Applications
- Personalized marketing
- Customer targeting
- Loyalty programs
- Product recommendations
- Revenue optimization

---

# Conclusion
This project demonstrates how unsupervised learning can identify hidden customer patterns. Businesses can use these insights to improve customer engagement, customer retention, and business decision-making.

