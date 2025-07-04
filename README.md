# Sales-forecasting-with-linear-regression
help to predict the future values from the dataset by the help of LINEAR REGRESSION

# 📈 Sales Forecasting with Linear Regression

## 🧩 Problem Statement
Businesses often struggle to estimate future sales based on past performance. Accurate sales forecasting helps in better inventory management, marketing strategies, and financial planning.

---

## 🎯 Objective
Build a **Linear Regression model** to predict future sales using historical sales data. The project includes data preprocessing, exploratory analysis, model training, evaluation, and forecasting.

---

## 📁 Dataset
The dataset used contains the following columns:

- `Date`: Date of the transaction
- `Product`: Product name or ID
- `Quantity`: Quantity sold
- `Revenue`: Revenue generated on that date

📂 Example dataset structure:
| Date       | Product | Quantity | Revenue |
|------------|---------|----------|---------|
| 2024-01-01 | A       | 100      | 1000    |

---

## 🔧 Tools & Technologies
- Python 3.x
- Pandas
- Numpy
- Scikit-learn
- Matplotlib
- Seaborn

---

## 🛠️ Steps Performed

### 1. Data Loading
- Read sales data from a CSV file.
- Parsed `Date` column into datetime format.

### 2. Data Preprocessing
- Handled null values.
- Aggregated sales monthly using `groupby`.
- Converted `Date` into numeric format using `.toordinal()`.

### 3. Model Building
- Used **Linear Regression** from `scikit-learn`.
- Trained on 80% of the data and tested on 20%.

### 4. Evaluation
- Evaluated using **Mean Squared Error (MSE)** and **R² Score**.
- Plotted **Actual vs Predicted Revenue**.

### 5. Forecasting
- Forecasted revenue for the next 6 months.
- Visualized future predictions alongside historical data.

---

## 📊 Results

### ✅ Model Performance
- **R² Score**: *Above 0.85* on clean aggregated data (actual score may vary)
- **MSE**: Dependent on dataset variability

### 📉 Visualizations
- Actual vs Predicted Revenue
- Future Sales Forecast (Line plot)
- Tabular view of forecasted monthly revenue

---
