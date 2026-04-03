# 🛒 SmartCart Customer Segmentation using K-Means

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Machine Learning](https://img.shields.io/badge/ML-Clustering-green)
![Status](https://img.shields.io/badge/Project-Completed-success)

---

## 📌 Problem Statement

SmartCart is an e-commerce platform that currently uses generic marketing strategies for all customers. This leads to inefficient campaigns, poor customer targeting, and missed opportunities to retain valuable users.

This project aims to solve this problem by building an intelligent **customer segmentation system** using **unsupervised machine learning** techniques.

---

## 🎯 Objective

* Segment customers based on purchasing behavior and engagement
* Identify high-value and low-engagement customers
* Support data-driven marketing decisions

---
## 📂 Dataset
Dataset used: `smartcart_customers.csv` (included in repository)

## 📊 Dataset Description

The dataset contains **2240 customer records** with features such as:

* 👤 Demographics (Age, Income, Education, Marital Status)
* 🛍️ Purchase Behavior (Wines, Fruits, Meat, etc.)
* 📈 Activity (Web visits, purchases)
* ⏱️ Recency (last purchase)
* ⚠️ Customer complaints

---

## ⚙️ Tech Stack

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn

---

## 🧠 Methodology

1. Data Cleaning & Preprocessing
2. Feature Scaling
3. Dimensionality Reduction (PCA)
4. K-Means Clustering
5. Evaluation using:

   * Elbow Method (WCSS)
   * Silhouette Score

---

## 📈 Results

* Determined optimal number of clusters using combined evaluation metrics
* Identified distinct customer segments such as:

  * High spenders
  * Low engagement users
  * Discount-driven customers

---

## 📁 Project Structure

```
Smart-Cart/
│
├── Smartcart_cust.ipynb
├── README.md
├── requirements.txt
```

---

## 🚀 How to Run

1. Clone the repository
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Open the notebook:

   ```bash
   jupyter notebook
   ```
4. Run all cells

---


## 🔮 Future Improvements

* Try DBSCAN / Hierarchical clustering
* Deploy as a web app using Streamlit
* Automate optimal cluster selection

---

## 👩‍💻 Author

**Mahathi**
Computer Science Undergraduate

---

