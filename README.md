# ✈️ Flight Price Prediction - EDA & Feature Engineering

## 📌 Executive Summary

This project focuses on **Exploratory Data Analysis (EDA)** and **Feature Engineering** for a **Flight Price Prediction** problem. The goal is to prepare and transform the raw flight dataset into a clean, structured format that can be effectively used for predictive modeling. This analysis reveals key trends, uncovers hidden patterns, and constructs meaningful features to improve model performance.

---

## 📊 Dataset Description

- **Source:** Kaggle / Open Data [(https://www.kaggle.com/datasets/shubhambathwal/flight-price-prediction/data)
- **Features include:**
  - Airline, Date of Journey, Source & Destination
  - Route, Duration, Total Stops, Additional Info
  - Price (Target variable)

---

## 🔍 EDA Highlights

- Checked for null values and handled them appropriately
- Analyzed distribution of categorical features like `Airline`, `Source`, `Destination`
- Visualized relationships between price and other variables
- Observed time-based features like journey date and duration

---

## ⚙️ Feature Engineering

- Converted `Date_of_Journey`, `Dep_Time`, `Arrival_Time` into datetime objects and extracted:
  - Day, Month, Hour, Minute
- Transformed categorical variables using `Label Encoding` and `One-Hot Encoding`
- Engineered new features from `Route` and `Duration`
- Removed irrelevant or redundant columns post transformation

---

## 🧰 Tools & Libraries Used

- Python 🐍
- Pandas
- NumPy
- Seaborn & Matplotlib (for visualization)
- Jupyter Notebook

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/flight-price-eda.git

## Install dependencies (preferably via virtual environment):
- pip install -r requirements.txt

