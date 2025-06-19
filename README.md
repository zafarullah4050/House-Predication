# House-Predication
# 🏠 House Price Prediction using Linear Regression

This project demonstrates how to apply **Linear Regression** on a real-world dataset of house listings to predict flat prices based on **Carpet Area (sqft)**.

---

## 📁 Dataset

- File: `house_prices.csv`
- Location: Thane (India)
- Columns used:
  - `Carpet Area` → Flat area in sqft (e.g., "500 sqft")
  - `Amount(in rupees)` → Price in textual format (e.g., "42 Lac", "1.40 Cr")

---

## 🎯 Objective

To train a **Linear Regression model** that predicts the **price (in Lac PKR)** of a flat using only its **Carpet Area**.

---

## 🔧 Steps Performed

### 1. **Data Loading**
```python
df = pd.read_csv("house_prices.csv")
