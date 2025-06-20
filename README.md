# 🛒 Market Basket Analysis using Apriori Algorithm

This project performs Market Basket Analysis on a grocery transaction dataset to uncover frequently bought item combinations using the Apriori algorithm.

## 📌 Problem Statement

Retailers can boost sales and customer satisfaction by analyzing customer transaction data to uncover patterns in product combinations. The goal is to identify association rules that suggest items frequently purchased together.

## 📂 Dataset

- **Groceries_dataset.csv**
  - `Member_number`: Customer ID
  - `Date`: Transaction date
  - `itemDescription`: Item purchased

## 🔍 Steps Performed

1. **Data Preparation**:
   - Grouped purchases by customer/date to form baskets
2. **Transaction Encoding**:
   - One-hot encoded the transactions
3. **Frequent Itemsets**:
   - Mined using Apriori algorithm (min support = 1%)
4. **Association Rules**:
   - Extracted rules using lift > 1 and sorted by confidence
5. **Visualization**:
   - Scatter plot of support vs. confidence

## 📈 Metrics Used

- Support
- Confidence
- Lift

## 📁 Files

- `Market_Basket_Analysis_Apriori.ipynb`: Full analysis notebook
- `Groceries_dataset.csv`: Dataset
- `README.md`: This file

## ✅ Requirements

```bash
pip install pandas mlxtend matplotlib seaborn
