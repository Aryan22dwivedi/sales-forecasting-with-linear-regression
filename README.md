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
![customer_segmentation ipynb - Visual Studio Code 04_07_2025 20_31_43](https://github.com/user-attachments/assets/b6c53e03-cbec-49ca-92b5-426a05480e70)

### 2. Data Preprocessing
- Handled null values.
- ![image](https://github.com/user-attachments/assets/abdbf05a-5919-4087-b527-a346f51b7b0e)

- Aggregated sales monthly using `groupby`.
- Converted `Date` into numeric format using `.toordinal()`.
![image](https://github.com/user-attachments/assets/ee179866-a6f4-4788-b311-e84c974b221f)

### 3. Model Building
- Used **Linear Regression** from `scikit-learn`.
- Trained on 80% of the data and tested on 20%.

### 4. Evaluation
- Evaluated using **Mean Squared Error (MSE)** and **R² Score**.
- ![image](https://github.com/user-attachments/assets/ee7f35a5-0437-4d37-96b2-88151f8bb063)

- Plotted **Actual vs Predicted Revenue**.
- ![image](https://github.com/user-attachments/assets/5943beca-8216-4d77-9d5a-6752e46e55f2)


### 5. Forecasting
- Forecasted revenue for the next 6 months.
- Visualized future predictions alongside historical data.

---

## 📊 Results

### ✅ Model Performance
- **R² Score**: *Above 0.85* on clean aggregated data
- **MSE**: Dependent on dataset variability

### 📉 Visualizations
- Actual vs Predicted Revenue
- Future Sales Forecast (Line plot)
- Tabular view of forecasted monthly revenue
![image](https://github.com/user-attachments/assets/6050da91-3345-4aa9-bb9a-788f78e2b463)

---
