# 📘 **E-Commerce Revenue Optimization Using Predictive Analytics & Pricing Strategies**

---

## ⭐ **1. Project Overview**

This project explores how predictive analytics and machine learning can be used to optimise pricing and revenue in an e-commerce environment. The analysis focuses on understanding customer purchasing behaviour, evaluating the impact of pricing and discounts on demand, and building forecasting models that support strategic pricing decisions.


---

## 🎯 **2. Business Problem**

E-commerce companies often struggle to balance competitive pricing, promotions, and profitability. This project answers key business questions such as:

- How does price influence customer demand?  
- What discount level maximises revenue instead of reducing it?  
- Can we reliably forecast revenue using historical purchasing patterns?  
- Which customers, products, or regions contribute most to revenue?  

The goal is to build a data-driven pricing optimisation framework.

---

## 📂 **3. Dataset Description**

### ⚠️ _Dataset Availability_

The original dataset is not included in this repository because it exceeds GitHub’s file size limit.  
However, all data cleaning, preprocessing, and feature engineering steps are fully documented within the Jupyter Notebook.

### 📊 _Dataset Structure_

The dataset contains anonymised e-commerce transactions with the following fields:

- **InvoiceNo** – transaction ID  
- **StockCode** – product reference  
- **Description** – product name  
- **Quantity** – number of units purchased  
- **InvoiceDate** – date and time  
- **UnitPrice** – price per unit  
- **CustomerID** – anonymised customer identifier  
- **Country** – customer country  

Total rows: 500,000+ transactions, ideal for advanced pricing and revenue modelling.

---

## 🛠️ **4. Tools & Technologies**

- **Python:** pandas, NumPy, scikit-learn, matplotlib  
- **Jupyter Notebook**  
- **Excel:** initial data checks  
- **Machine Learning Models:** Linear Regression, Random Forest Regressor  
- **Metrics:** MAE, MSE, RMSE, R²  

These tools support an end-to-end workflow from data cleaning to model development and insight generation.

---

## 🔄 **5. Project Workflow**

### **a) Data Cleaning & Preparation**

- Removed duplicates and invalid entries  
- Standardised date formats  
- Handled missing values  
- Created revenue variable: `Quantity × UnitPrice`  
- Treated outliers using statistical thresholds  

---

### **b) Exploratory Data Analysis (EDA)**

- Revenue trends across months, products, and regions  
- Impact of discounts and pricing on demand  
- Identification of high-value customers and seasonal patterns  
- Behaviour of top-selling product categories  

---

### **c) Feature Engineering**

Created predictive features such as:

- Average Order Value (AOV)  
- Purchase frequency  
- Seasonal indicators (month, quarter, year)  
- Discount elasticity  
- Product-level revenue contribution  
- Time-based demand features  

---

### **d) Model Development**

Steps taken:

- Train-test split  
- Model training using regression and ensemble algorithms  
- Hyperparameter tuning for performance improvement  
- Model comparison using RMSE, MAE, and R²  

**Random Forest** delivered the best performance due to its ability to capture complex, nonlinear relationships.

---

## 📈 **6. Key Insights & Findings**

- **Moderate discounts increase demand**, but excessive discounts reduce profitability.  
- **Price elasticity varies by product category**, meaning not all items respond the same to price changes.  
- **A small percentage of customers drive the majority of revenue**, indicating opportunities for personalised pricing.  
- **Seasonality strongly influences demand**, making time-based features essential for forecasting.  
- **The predictive model accurately forecasts revenue trends**, supporting future pricing and inventory decisions.  

These insights show how analytics can guide smarter, more profitable pricing strategies.

---

## 🧠 **7. Skills Demonstrated**

- End-to-end machine learning pipeline development  
- Working with large datasets (500k+ rows)  
- Advanced EDA and feature engineering  
- Predictive modelling for real business decisions  
- Communicating complex results in simple business terms  
- Applying analytics to revenue optimisation and pricing strategies  

---

## 🚀 **8. Future Improvements**

Potential enhancements include:

- Adding competitor pricing data  
- Including sentiment analysis from customer reviews  
- Testing advanced models like XGBoost or Neural Networks  
- Deploying the model via a Streamlit or Power BI dashboard  
- Integrating reinforcement learning for dynamic pricing  

---

## 📁 **9. Repository Contents**

- `revenue_optimisation.ipynb` – full analysis and modelling notebook  
