# 🛒 Market Basket Analysis using Apriori Algorithm

This project implements **Market Basket Analysis** to discover associations between products purchased together. It uses the **Apriori algorithm** to generate frequent itemsets and association rules from transaction data.

---

## 🚀 Project Overview

Market Basket Analysis is a data mining technique used in retail to understand customer purchasing behavior. It helps answer questions like:

- Which products are frequently bought together?
- How can we improve cross-selling strategies?
- How should products be placed in stores?

In this project, we apply **association rule mining** to find meaningful patterns.

---

## 🗂 Dataset

- Input: Transactional dataset  
- Each row represents a customer transaction  
- Each column represents an item (1 = purchased, 0 = not purchased)



---

## 🔧 Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- mlxtend (for Apriori & Association Rules)  
- Jupyter Notebook / Google Colab  

---

## 🧪 Steps Performed

### 1. Data Loading
- Loaded transaction dataset
- Converted data into suitable one-hot encoded format

### 2. Data Preprocessing
- Cleaned data
- Transformed transactions into binary matrix

### 3. Frequent Itemset Generation
Used **Apriori algorithm** to find frequent itemsets based on:
- Minimum support threshold

### 4. Association Rule Mining
Generated rules using:
- Support  
- Confidence  
- Lift  

---

## 📐 Key Concepts

### Support
How frequently an itemset appears in the dataset.

### Confidence
Probability that item B is purchased when item A is purchased.

### Lift
Strength of the association:
- Lift > 1 → Positive correlation  
- Lift = 1 → No correlation  
- Lift < 1 → Negative correlation  

---


Meaning:
Customers who buy **Milk** are 1.25 times more likely to buy **Bread**.

---

## ▶️ How to Run

1. Clone the repository:
```bash
git clone https://github.com/your-username/market-basket-analysis.git
