# 📊 Apple Inc. EBITDA Forecast (2009–2030)

This project analyzes Apple Inc.'s historical financial data and forecasts future **EBITDA (Earnings Before Interest, Taxes, Depreciation, and Amortization)** using **Linear Regression**. The model predicts EBITDA values for the years 2026 to 2030, based on trends observed from 2009 to 2024.

---

## 📁 Dataset

- **Source**: Apple Inc. financial records (2009–2024)
- **Format**: `.csv`
- **Features Used**:
  - Year
  - Revenue (in millions)
  - Net Income (in millions)
  - Gross Margin (%)
  - Employees
  - EBITDA (Target Variable)

---

## 🧠 Machine Learning Approach

- **Model Used**: Linear Regression
- **Library**: Scikit-learn (`sklearn`)
- **Training Feature**: `Year`
- **Target Variable**: `EBITDA`

---

## 📈 Forecasted Results (2026–2030)

| Year | Predicted EBITDA (in Million USD) |
|------|-----------------------------------|
| 2026 | $158,124.56                       |
| 2027 | $163,761.24                       |
| 2028 | $169,397.91                       |
| 2029 | $175,034.59                       |
| 2030 | $180,671.27                       |

> _Note: Values are approximations based on historical linear growth._

---

## 📌 Technologies Used

- Python 🐍
- Pandas & NumPy for data analysis
- Scikit-learn for modeling
- Matplotlib for visualization
- Jupyter Notebook for development

---

## 📚 Key Insights

- EBITDA shows a strong upward trend year over year.
- The linear model provides a simple yet effective forecast for short-term planning.
- This project demonstrates the power of financial time series forecasting using machine learning.

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/HariniMathankumar/APPLE_COMPANY_EBITDA_PREDICTION.git
   cd APPLE_COMPANY_EBITDA_PREDICTION
2.Open the Jupyter Notebook:

bash
Copy
Edit
jupyter notebook

3.Run EBITDA_Prediction.ipynb to view analysis and predictions.
