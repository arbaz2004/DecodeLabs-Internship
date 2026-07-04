# Customer Segmentation using K-Means Clustering

## Overview

This project performs **Customer Segmentation** using **Unsupervised Machine Learning** techniques. The objective is to group customers with similar purchasing behavior to help businesses understand different customer segments and make data-driven decisions.

The project was completed as part of the **DecodeLabs Data Science Internship – Project 3**.

---

## Problem Statement

Businesses often have large amounts of customer transaction data but lack insights into different customer groups. By applying clustering techniques, customers can be segmented based on purchasing patterns, allowing organizations to improve marketing strategies, customer retention, and product recommendations.

---

## Dataset

The dataset contains **1,200 customer transaction records** with **14 features**, including:

- Order ID
- Customer ID
- Date
- Product
- Quantity
- Unit Price
- Total Price
- Items in Cart
- Payment Method
- Order Status
- Coupon Code
- Referral Source
- Shipping Address
- Tracking Number

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Machine Learning Techniques

- Data Cleaning
- Missing Value Handling
- One-Hot Encoding
- StandardScaler
- Principal Component Analysis (PCA)
- K-Means Clustering
- Elbow Method
- Silhouette Score

---

## Project Workflow

1. Load Dataset
2. Data Cleaning
3. Handle Missing Values
4. Exploratory Data Analysis (EDA)
5. Feature Selection
6. One-Hot Encoding
7. Feature Scaling
8. Principal Component Analysis (PCA)
9. Elbow Method
10. Silhouette Score
11. K-Means Clustering
12. Cluster Analysis
13. Customer Segmentation

---

## Results

- Dataset cleaned successfully
- Missing values handled
- Categorical features encoded
- Features standardized using StandardScaler
- PCA applied for dimensionality reduction
- Optimal number of clusters determined using:
  - Elbow Method
  - Silhouette Score
- Customers segmented into **6 clusters**
- Business insights generated from cluster characteristics

---

## Project Structure

```
Customer-Segmentation-KMeans/
│
├── Customer_Segmentation.ipynb
├── Dataset for Data Analytics(2).xlsx
├── README.md
├── requirements.txt
└── .gitignore
```

---

## Installation

Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/Customer-Segmentation-KMeans.git
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the notebook

```bash
jupyter notebook
```

---

## Future Improvements

- Customer Lifetime Value (CLV) Analysis
- RFM Segmentation
- Interactive Dashboard using Streamlit
- Automated Customer Persona Generation
- Model Deployment

---

## Author

**Mohammed Arbaz**

B.Tech Artificial Intelligence & Machine Learning

DecodeLabs Data Science Internship Project

---

## License

This project is created for educational and internship purposes.
