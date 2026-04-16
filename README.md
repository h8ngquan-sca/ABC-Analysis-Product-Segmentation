# ABC-Analysis-Product-Segmentation
A data-driven Supply Chain Analytics workflow that leverages retail transaction data to build an actionable ABC-XYZ matrix for inventory optimization.
# 📦 Supply Chain Analytics: ABC-XYZ & Demand Planning

## 📌 Project Overview
This project simulates a real-world Supply Chain Analytics workflow using transactional retail data.

The objective is to:
- Segment products based on revenue contribution (ABC)
- Analyze demand variability (XYZ)
- Combine into ABC-XYZ matrix for inventory strategy

---

## 🧠 Business Problem

How can we:
- Identify critical SKUs?
- Handle demand uncertainty?
- Optimize inventory decisions?

---

## 🗂 Dataset
- UCI Online Retail II (~1M transactions)

---

## ⚙️ Methodology

### 1. Data Cleaning
- Removed cancellations, invalid transactions
- Handled missing values

### 2. Customer Segmentation
- Wholesale vs D2C classification

### 3. ABC Analysis
- Based on cumulative revenue contribution

### 4. XYZ Analysis
- Coefficient of Variation (CV)

### 5. ABC-XYZ Matrix
- 9 product segments

---

## 📊 Key Insights

- ~20% SKUs contribute ~80% revenue (Pareto effect)
- High variability SKUs (Z-class) drive inventory risk
- AZ segment requires special attention due to high revenue + volatility
- Wholesale customers skew demand patterns

---

## 🚀 Business Recommendations

| Segment | Strategy |
|--------|---------|
| AX | High service level, low safety stock |
| AZ | Increase safety stock |
| BX | Stable replenishment |
| CZ | Consider discontinuation |

---

## 🛠 Tech Stack
- Python (Pandas, NumPy)
- Matplotlib / Seaborn
- Time-series analysis

---

## 📈 Future Improvements
- Advanced forecasting models (Prophet, ARIMA)
- Inventory simulation
- Service level optimization