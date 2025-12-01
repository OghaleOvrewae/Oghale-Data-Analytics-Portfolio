# E-Commerce Revenue Optimization Using Predictive Analytics & Pricing Strategies

## 1. Project Overview
This project applies predictive analytics and machine learning to optimise revenue for an e-commerce business. The aim is to analyse customer behaviour, understand how pricing and discounts affect demand, and build forecasting models that support data-driven pricing decisions.

---

## 2. Dataset
This project uses an online retail transactions dataset with:

- Around 540,000+ rows of transactions  
- 8 columns, including:  
  - `InvoiceNo` – transaction ID  
  - `StockCode` – product code  
  - `Description` – product description  
  - `Quantity` – units ordered  
  - `InvoiceDate` – date and time of purchase  
  - `UnitPrice` – price per unit  
  - `CustomerID` – anonymous customer ID  
  - `Country` – customer location  

The dataset represents real-world e-commerce behaviour and is ideal for revenue and pricing analysis.

### Dataset Availability
The original dataset used in this project is not included in this repository due to file size limitations.
However, the full analysis, preprocessing steps, and feature engineering workflow can be found in the Jupyter Notebook.

---

## 3. Tools & Techniques
- **Python:** pandas, NumPy, scikit-learn, matplotlib  
- **Jupyter Notebook**  
- **Excel** for initial checks and exploration  
- **Machine Learning Models:** e.g. Linear Regression, Random Forest Regressor  
- **Metrics:** MAE, RMSE, R² to evaluate model performance  

---

## 4. Workflow

### a) Data Cleaning & Preparation
- Removed duplicates and invalid records  
- Handled missing values in key fields  
- Converted dates into proper datetime formats  
- Created additional variables such as total revenue per transaction  

### b) Exploratory Data Analysis (EDA)
- Analysed revenue trends over time  
- Explored relationships between discounting, quantity, and revenue  
- Identified high-value products, customers, and regions  

### c) Feature Engineering
- Built features related to:
  - Customer purchasing frequency  
  - Average order value  
  - Seasonal and time-based patterns  
  - Product and country-level behaviour  

### d) Modelling
- Split the data into **training** and **test** sets  
- Trained regression-based models to predict revenue  
- Compared models using evaluation metrics  
- Interpreted which features most strongly influenced revenue  

---

## 5. Key Insights
- Pricing and discounting have a clear impact on sales quantity and revenue.  
- Some products and regions consistently generate higher revenue.  
- There are customer segments that respond more strongly to discounts.  

These insights can support decisions around targeted promotions and dynamic pricing strategies.

---

## 6. Repository Contents
- `Revenue Optimisation.ipynb` – main Jupyter Notebook with the full analysis and models  
- `data.csv` – transactional dataset used for analysis (anonymised)  
 
---

## 7. What I Learned
- Applying predictive analytics to real-world business questions   
- Improving data quality before modelling  
- Building and evaluating pricing-related forecasting models  
- Turning technical analysis into clear, business-focused insights  

---

## 8. Future Improvements
- Incorporate competitor pricing or marketing campaign data  
- Test additional models such as XGBoost  
- Deploy the model behind a simple dashboard or API  
- Add a Power BI or Python-based dashboard for live revenue monitoring
