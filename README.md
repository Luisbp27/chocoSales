# 🍫 Chocolate Sales Analysis with Clustering and PCA

This project is a full data analysis pipeline on the [Chocolate Sales Dataset](https://www.kaggle.com/datasets/atharvasoundankar/chocolate-sales), designed to explore sales behavior, profitability, and commercial segmentation using clustering and PCA.

---

## 🚀 Project Overview

The main goals of this project are:

1. **Understand the overall sales landscape**: revenue, order size, geographical distribution.
2. **Analyze profit margins across order segments**: small, medium, and large.
3. **Identify high-impact sales behaviors** using KPIs like order frequency, profit per order, and order type distribution.
4. **Cluster salespeople** by their commercial behavior (not just volume), using KMeans.
5. **Apply PCA** to evaluate variable contribution and optimize clustering results.

## 🧠 Key Insights

- Large orders generate the **highest total profit**, but not always the best **profit margin**.
- There is **no clear linear correlation** between focusing on large orders and overall profit.
- After applying **PCA**, we reduced our feature set to 5 high-impact variables and improved cluster coherence.
- The sales team exhibits different commercial profiles, such as "High-volume sellers", "Margin optimizers", and "Balanced performers".

## 📁 Project Structure

```bash
.
├── report.ipynb   # Main Jupyter Notebook with all analysis
├── README.md                 # This file
├── requirements.txt          # List of Python dependencies
└── data/
    └── Chocolate Sales.csv   # Raw dataset from Kaggle
```

## Setup Instructions

To run this project locally, follow these steps:

1. Clone the repository:

```bash
git clone https://github.com/your-username/chocoSales.git
cd chocoSales
```

2. Create a virtual environment (optional but recommended):

```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```

3. Install the required packages:

```bash
pip install -r requirements.txt
```

Now you can run the Jupyter Notebook `report.ipynb` to explore the analysis and insights.
