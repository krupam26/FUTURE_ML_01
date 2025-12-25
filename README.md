# 📊 Sales Forecasting Project (Kaggle → Power BI)

## 🔍 Project Overview

This project focuses on **time series sales forecasting** using historical sales data. The model is developed in **Kaggle (Python)** and the forecasted results are exported for **visualization and analysis in Power BI**.

The goal is to predict future sales accurately and present insights through clean, minimal dashboards.

---

## 🧰 Tools & Technologies

* **Platform:** Kaggle Notebook
* **Programming Language:** Python
* **Libraries Used:**

  * pandas
  * numpy
  * matplotlib
  * seaborn
  * prophet
* **Visualization Tool:** Power BI
* **Version Control:** GitHub

---

## 📁 Project Structure

```
FUTURE_ML_01/
│── notebook.ipynb        # Kaggle notebook (model training & forecasting)
│── sales_forecast.csv    # Forecast output for Power BI
│── powerbi_sales_data    # PowerBI combined data 
│── README.md             # Project documentation
```

---

## 🔄 Workflow

1. **Data Loading & Cleaning**

   * Imported historical sales data
   * Handled missing values and date formatting

2. **Exploratory Data Analysis (EDA)**

   * Trend and seasonality analysis
   * Visualization of historical patterns

3. **Model Building**

   * Used Facebook Prophet for time series forecasting
   * Tuned seasonality and trend components

4. **Model Evaluation**

   * Evaluated using **SMAPE**
   * Achieved ~5–6% SMAPE indicating strong performance

5. **Forecast Generation**

   * Generated future sales predictions
   * Exported forecast as CSV

6. **Power BI Visualization**

   * Imported CSV into Power BI
   * Created KPI cards and trend dashboards

---

## 📤 Output

* **Forecast file:** `sales_forecast.csv`
* Columns:

  * `ds` – Date
  * `yhat` – Predicted sales
  * `yhat_lower` – Lower confidence bound
  * `yhat_upper` – Upper confidence bound

---

## 📈 Use Case

* Sales planning
* Demand forecasting
* Business performance analysis
* Dashboard-driven decision making

---

## 🚀 How to Run

1. Open the notebook in **Kaggle** or **Jupyter Notebook**
2. Install required libraries:

```bash
pip install pandas numpy matplotlib prophet
```

3. Run all cells to generate forecast
4. Export CSV and load into Power BI

---

## 📝 Notes

* Large datasets are not included due to GitHub file size limits
* Forecast results are optimized for Power BI consumption

---

## 👤 Author

**Krupa Mehta**
Engineering Student | Data Analytics & Visualization

---

⭐ If you find this project useful, feel free to star the repository!
