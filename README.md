# 📊 Sales Forecasting & Demand Prediction

An end-to-end **Sales Forecasting and Business Intelligence** project using **Machine Learning and Power BI** to predict future sales, analyze trends, and provide actionable insights for business decision-making.

---

## 🔹 Project Objective
To build a complete sales forecasting system that:
- Predicts future sales from historical retail data  
- Analyzes product and regional performance  
- Visualizes insights in an interactive Power BI dashboard  
- Supports data-driven business decisions  

---

## 🔹 Dataset
The dataset contains multi-year retail sales data including:
- Order Date  
- Sales Amount  
- Product Category  
- Region  

The data was cleaned, aggregated monthly, and prepared for time-series forecasting.

---

## 🔹 Workflow
1. Data cleaning and preprocessing  
2. Exploratory Data Analysis (EDA)  
3. Monthly sales aggregation  
4. Time-series forecasting using Prophet  
5. Model evaluation (MAE, RMSE, MAPE)  
6. Power BI dashboard creation  
7. Business insights and recommendations  

---

## 🔹 Technologies Used
- Python (Pandas, NumPy, Prophet, Matplotlib)  
- Power BI  
- Time Series Forecasting  
- Data Analysis & Visualization  

---

## 🔹 Features
- Monthly sales trend analysis  
- Actual vs Forecasted sales  
- Category-wise and region-wise sales  
- Growth and revenue KPIs  
- Interactive Power BI dashboard  

---

## 🔹 Business Insights
- Sales peak in late-year months, showing strong seasonality  
- Technology is the highest revenue-generating category  
- East and West regions drive most of the revenue  
- The forecast predicts strong growth in the next 12 months  

---

## 🔹 How to Run the Project

### 1. Clone the Repository
```
git clone <your-github-repo-link>
cd sales-forecasting-project
```

2. Install Required Libraries
```
pip install pandas numpy matplotlib prophet scikit-learn
```

3. Run the Jupyter Notebooks
Open Jupyter Notebook or Jupyter Lab and run:
```
notebooks/01_data_cleaning.ipynb  
notebooks/02_eda.ipynb  
notebooks/03_forecasting.ipynb
```
These notebooks will:
- Clean the data
- Perform EDA
- Train the forecasting model
- Generate the forecast output
- The processed files will be saved in:
```
data/processed/
```

4. Open Power BI Dashboard
Open the .pbix file inside the dashboard/ folder using Power BI Desktop.
Make sure the Power BI file points to:
```
data/processed/monthly_sales.csv  
data/processed/forecast.csv
```
Refresh the data to view updated visuals.

---

## 🔹 Business Insights

- Sales peak in late-year months, showing strong seasonality
- Technology is the highest revenue-generating category
- East and West regions drive most of the revenue
- The forecast predicts strong growth in the next 12 months

---

## 🔹 Project Structure

data/          → Raw and processed datasets  
notebooks/     → Data cleaning, EDA, and forecasting notebooks  
models/        → Trained forecasting models  
dashboard/     → Power BI dashboard  
report/        → Final PDF report  

---

## 🔹 Outcome

This project demonstrates real-world skills in:
- Time-series forecasting
- Machine learning
- Business intelligence
- Data storytelling
It provides a complete, portfolio-ready solution for retail sales forecasting and analytics.
