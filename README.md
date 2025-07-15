# Prodigy_ml_Task2
# 🛍️ Customer Segmentation using K-Means Clustering

## 📌 Project Overview

This project applies the K-Means clustering algorithm to segment customers of a retail store based on their **Annual Income** and **Spending Score**. Customer segmentation helps businesses target marketing strategies and personalize services more effectively.

---

## 📊 Dataset

- **Source**: [Kaggle - Customer Segmentation](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)
- **Filename**: `Mall_Customers.csv`
- **Features used**:
  - `Annual Income (k$)`
  - `Spending Score (1-100)`

---

## 🧠 Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn (KMeans, StandardScaler)

---

## 🧪 Steps Performed

1. **Data Loading & Exploration**:
   - Loaded dataset using pandas
   - Checked for missing values and data types

2. **Feature Selection**:
   - Chose `Annual Income` and `Spending Score` as clustering features

3. **Preprocessing**:
   - Scaled the features using `StandardScaler`

4. **Elbow Method**:
   - Identified optimal number of clusters (K) using the Elbow plot

5. **K-Means Clustering**:
   - Applied KMeans algorithm with optimal K (e.g., 5)

6. **Visualization**:
   - Used Seaborn scatter plot to visualize clusters

---

## 📈 Result

The customer base was successfully segmented into **5 distinct groups** based on spending behavior and income. This segmentation can help in:

- Targeted marketing campaigns
- Personalized promotions
- Understanding customer value groups

---


## 💡 Future Work

- Include additional features like Age and Gender
- Compare with DBSCAN or Hierarchical Clustering
- Build a dashboard to interactively view clusters

---
