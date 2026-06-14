# 🛒 SmartCart — E-commerce Customer Segmentation System

> *"Stop guessing. Start knowing your customers."*

![Python](https://img.shields.io/badge/Python-3.x-blue?style=flat-square&logo=python)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=flat-square&logo=jupyter)
![ML](https://img.shields.io/badge/ML-KMeans%20Clustering-green?style=flat-square)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen?style=flat-square)

---

## 🎯 What is SmartCart?

SmartCart is a **machine learning-powered customer segmentation system** built for e-commerce businesses. Using **K-Means Clustering**, it groups customers into meaningful segments based on their **income, spending behavior, family profile, and engagement patterns** — helping businesses target the right customers with the right strategy.

---

## 📊 Customer Segments Discovered

| Cluster | Nickname | Profile | Strategy |
|---------|----------|---------|----------|
| 🟠 C0 | Family Shoppers | More children, poor campaign response, low spending | Discounts & Coupons |
| 🔵 C1 | Loyal Buyers | Fewer children, slightly older, avg response | Loyalty Programs |
| 🟡 C2 | Digital Browsers | Alone, avg income, high web visits | Sales & Heavy Discounts |
| 🟢 C3 | High-Value Singles | Best campaign response, fewer children, alone | ⭐ Premium Services (Best ROI) |

---

## 🧠 Tech Stack

- **Python** — Core language
- **Pandas & NumPy** — Data wrangling
- **Matplotlib & Seaborn** — Visualizations
- **Scikit-learn** — KMeans Clustering, preprocessing
- **Jupyter Notebook** — Analysis environment

---

## 📁 Project Structure
smartcart-customer-segmentation/

│

├── smart_cart.ipynb          # Main analysis notebook

├── smartcart_customers.csv   # Customer dataset

└── README.md

---

## 🚀 How to Run

```bash
# 1. Clone the repo
git clone https://github.com/Bhoomi-1401/smartcart-customer-segmentation.git

# 2. Install dependencies
pip install pandas numpy matplotlib seaborn scikit-learn jupyter

# 3. Launch notebook
jupyter notebook smart_cart.ipynb
```

---

## 🔍 Key Steps in the Analysis

1. **Data Cleaning** — Handle nulls, outliers, feature engineering
2. **EDA** — Explore spending patterns, income distribution, family profiles
3. **Preprocessing** — Scaling, encoding
4. **Optimal K** — Elbow Method + Silhouette Score
5. **Clustering** — KMeans with best K
6. **Profiling** — Detailed cluster analysis & business recommendations

---

## 💡 Business Insight

> **Cluster C3** delivers the **best ROI** — high-value singles who respond well to campaigns and prefer premium services. This is your golden customer segment! 🏆

---

## 👩‍💻 Author

**Bhoomi** — [@Bhoomi-1401](https://github.com/Bhoomi-1401)

---

⭐ *If you found this helpful, drop a star!*
