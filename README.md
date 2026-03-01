# 📊 Customer Lifetime Value Prediction Using Machine Learning

## 🚀 Project Overview

Customer Lifetime Value (LTV) prediction helps businesses estimate the total revenue a customer is expected to generate throughout their relationship with a company.

This project develops a complete data analytics and machine learning solution to analyze retail transaction data and predict customer lifetime value. The solution enables organizations to identify valuable customers, optimize marketing strategies, and improve customer retention using data-driven insights.

---

## 🎯 Business Objective

* Predict long-term customer value
* Identify high-value customers
* Improve customer retention strategies
* Optimize marketing investment
* Support business decision-making using analytics

---

## 🧠 Project Workflow

```
Raw Dataset
   ↓
Data Cleaning
   ↓
Feature Engineering (RFM Analysis)
   ↓
Machine Learning Model Training
   ↓
Customer Lifetime Value Prediction
   ↓
Customer Segmentation
   ↓
Business Insights & Reports
```

---

## 🗂️ Project Structure

```
customer-lifetime-value-prediction/
│
├── README.md
├── requirements.txt
├── LICENSE
│
├── data/
│   ├── raw/
│   │   └── online_retail.csv
│   │
│   └── processed/
│       └── cleaned_data.csv
│
├── notebooks/
│   └── 01_ltv_analysis.ipynb
│
├── models/
│   └── ltv_prediction_model.pkl
│
├── outputs/
│   ├── customer_ltv_predictions.csv
│   └── feature_importance.csv
│
├── visualizations/
│   ├── segment_distribution.png
│   └── ltv_prediction_chart.png
│
├── reports/
│   ├── project_report.pdf
│   └── business_recommendations.pdf
│
└── docs/
    └── project_explanation.txt
```

---

## 📂 Dataset Information

The project uses the **Online Retail Dataset**, which contains transactional purchase records from an online retail store.

### Dataset Features

* Invoice Number
* Product Description
* Quantity Purchased
* Invoice Date
* Unit Price
* Customer ID
* Country

---

## ⚙️ Technologies Used

* Python
* Pandas & NumPy
* Scikit-learn
* Matplotlib & Seaborn
* Machine Learning (Random Forest Regression)
* Google Colab
* GitHub

---

## 🔧 Data Preprocessing

The following preprocessing steps were performed:

* Removed cancelled transactions
* Filtered invalid quantity and price values
* Handled missing customer identifiers
* Converted date columns into datetime format
* Generated total sales feature

Processed dataset:

```
cleaned_data.csv
```

---

## 📈 Feature Engineering (RFM Model)

Customer-level behavioral features were created:

* **Recency** – Days since last purchase
* **Frequency** – Number of transactions
* **Monetary** – Total customer spending

These features enable effective customer behavior modeling.

---

## 🤖 Machine Learning Model

A **Random Forest Regression** algorithm was used to predict customer lifetime value.

### Model Output

Saved trained model:

```
models/ltv_prediction_model.pkl
```

---

## 👥 Customer Segmentation

Customers were categorized into three segments:

| Segment      | Business Strategy            |
| ------------ | ---------------------------- |
| High Value   | Loyalty & retention programs |
| Medium Value | Promotional engagement       |
| Low Value    | Re-engagement campaigns      |

---

## 📊 Visualizations

### Customer Segment Distribution

![Segment Distribution](visualizations/segment_distribution.png)

### Predicted Customer Lifetime Value

![LTV Prediction](visualizations/ltv_prediction_chart.png)

---

## 📌 Key Insights

* A small group of customers generates the majority of revenue.
* Customer spending behavior strongly influences lifetime value.
* Frequent customers demonstrate higher profitability.
* Data-driven segmentation improves marketing effectiveness.

---

## 📑 Project Reports

* **project_report.pdf** – Technical project documentation
* **business_recommendations.pdf** – Strategic business insights

---

## ✅ Project Outputs

* Customer LTV Prediction Dataset
* Feature Importance Analysis
* Trained Machine Learning Model
* Analytical Visualizations
* Business Recommendation Report

---

## ▶️ How to Run the Project

### Install Required Libraries

```
pip install -r requirements.txt
```

### Run Analysis

Open notebook:

```
notebooks/01_ltv_analysis.ipynb
```

---

## 🔮 Future Enhancements

* Real-time customer prediction system
* Integration with CRM platforms
* Automated marketing recommendation engine
* Advanced predictive modeling techniques

---

## 👨‍💻 Author

**MANOJRAJ G**
Data Analytics & Machine Learning Enthusiast

---

## 📜 License

This project is licensed under the MIT License.
