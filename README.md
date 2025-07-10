# 🛍️ Customer Segmentation using K-Means Clustering

This project applies **K-Means Clustering** on real-world **retail customer transaction data** to segment customers based on their **purchase behavior**. The goal is to help businesses understand and target different customer groups more effectively.

## 📌 Project Overview

- **Technique Used**: Unsupervised Machine Learning (K-Means Clustering)
- **Dataset**: [Online Retail Dataset from Kaggle](https://www.kaggle.com/datasets/lakshmi25npathi/online-retail-dataset)
- **Approach**: RFM (Recency, Frequency, Monetary) Analysis + Clustering

---

## 📊 RFM Feature Engineering

| Metric | Description |
|--------|-------------|
| **Recency** | Days since the customer last purchased |
| **Frequency** | Total number of purchases made |
| **Monetary** | Total money spent by the customer |

---

## 🔍 Steps Followed

1. **Data Cleaning**  
   Removed null values, duplicates, and negative quantities

2. **RFM Analysis**  
   Created Recency, Frequency, and Monetary features per customer

3. **Data Scaling**  
   Standardized the RFM features using `StandardScaler`

4. **Finding Optimal Clusters**  
   Used the **Elbow Method** to determine the best number of clusters (k=4)

5. **Clustering**  
   Applied **K-Means** and assigned each customer to a segment

6. **Visualization**  
   Reduced dimensions using PCA and plotted clusters in 2D

---

## 💡 Cluster Insights

| Cluster | Summary |
|---------|---------|
| 0 | ⭐ **Loyal Customers** – frequent and active |
| 1 | ⚠️ **At-Risk Customers** – inactive recently |
| 2 | 👑 **Super VIPs** – extremely frequent and high-value |
| 3 | 💎 **High-Value Actives** – recent, frequent, valuable |

---

## 📁 Files in this Repo

- `kmeans_customer_segmentation.ipynb` – Complete notebook
- `Customer_Segmentation_Report.docx` – Final report
- `Customer_Segmentation_Presentation.pptx` – Summary slides

---

## 📌 Tools & Libraries

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Scikit-learn (KMeans, StandardScaler, PCA)
- Jupyter Notebook

---

## ✅ Conclusion

This project successfully demonstrates how unsupervised learning can help businesses **identify key customer segments**, enabling personalized marketing and improved retention strategies.

---

## 📬 Contact

Feel free to reach out for collaboration or questions!  
**Intern** @ Indolike  
**Email**: your.email@example.com
