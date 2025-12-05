![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Data Cleaning](https://img.shields.io/badge/Data%20Cleaning-4CAF50?style=for-the-badge)
![EDA](https://img.shields.io/badge/EDA-2196F3?style=for-the-badge)
![Supply Chain](https://img.shields.io/badge/Supply%20Chain-FFC107?style=for-the-badge)



# Supply Chain Data Cleaning & Exploratory Data Analysis (EDA)


----------------------------------------
📦 SUPPLY CHAIN DATA CLEANING & EDA
----------------------------------------

This project demonstrates a full end‑to‑end data cleaning and exploratory data analysis workflow using a synthetic supply chain dataset. The dataset was intentionally made messy (missing values, duplicates, inconsistent formatting) to replicate real business data issues.

----------------------------------------
PROJECT PURPOSE (BUSINESS PROBLEM)
----------------------------------------

Supply chain teams rely on accurate data for:
- Inventory forecasting
- Shipping cost optimization
- Category performance analysis
- Customer satisfaction tracking

Real-world data is often incomplete or inconsistent.  
This project shows how to transform messy datasets into clean, analysis-ready ones.

----------------------------------------
KEY FEATURES
----------------------------------------

- Synthetic dataset creation  
- Simulated messy data conditions  
- Duplicate removal  
- Missing value imputation (mean/median/mode)  
- Text cleanup & standardization  
- Exploratory Data Analysis (EDA)  
- Business insights extraction  

----------------------------------------
SKILLS DEMONSTRATED
----------------------------------------

- Data Cleaning & Preprocessing  
- Handling Missing Values  
- Duplicate Detection  
- Categorical & Numerical Analysis  
- Correlation Analysis  
- Python (Pandas, NumPy, Datetime)  
- Documentation & Insight Reporting  

----------------------------------------
DATASET OVERVIEW
----------------------------------------

Columns:
- Transaction_ID — Unique transaction ID  
- Date — Purchase date  
- Product_Category — Laptop, Smartphone, etc.  
- Unit_Price — Price per item  
- Quantity — Units ordered  
- Shipping_Cost — Shipping charges  
- Shipping_Method — Standard / Express / Overnight / International  
- Customer_Rating — Rating 1–5  

Noise Added:
- 10% missing ratings  
- 5% missing shipping methods  
- 2% missing prices  
- 200 duplicate rows  

----------------------------------------
WORKFLOW DIAGRAM
----------------------------------------

Data Generation  
↓  
Messy Data Simulation  
↓  
Load & Inspect  
↓  
Data Cleaning  
  . Remove Duplicates  
  . Fill Missing Values  
  . Fix Text Inconsistencies  
↓  
Exploratory Data Analysis (EDA)  
↓  
Insights  

----------------------------------------
BEFORE vs AFTER CLEANING
----------------------------------------

Missing Ratings       → Filled using mean  
Missing Shipping      → Filled using mode  
Missing Prices        → Filled using median  
Duplicate Rows        → Removed (200)  
Text Issues           → Standardized (Title Case + strip)  

----------------------------------------
EXPLORATORY DATA ANALYSIS (EDA)
----------------------------------------

1. Categorical vs Categorical  
2. Categorical vs Numerical  
3. Numerical vs Numerical (correlation matrix)  

----------------------------------------
KEY INSIGHTS
----------------------------------------

- Smartphones & Laptops have the most transactions  
- Overnight shipping used more for high-price items  
- Customer ratings do NOT strongly depend on price  
- Shipping cost increases with order quantity  
- All text inconsistencies cleaned  

----------------------------------------
FUTURE ENHANCEMENTS
----------------------------------------

- Power BI / Tableau dashboard  
- Predictive modeling (price, rating, shipping cost)  
- Outlier detection  
- SQL analytics  
- API integration  

----------------------------------------
LICENSE
----------------------------------------

Open-source for education and portfolio use.

----------------------------------------
END OF README
----------------------------------------
