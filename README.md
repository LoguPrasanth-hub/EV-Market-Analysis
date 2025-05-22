# 🚗 EV & Vehicle Sales Segmentation Project
This project focuses on analyzing India's vehicle registration trends and electric vehicle (EV) adoption patterns to recommend the most viable vehicle type for manufacturing. It combines traditional vehicle sales data with electric vehicle registration insights to support data-driven manufacturing strategy decisions.

# 🎯 Project Goals
Identify which vehicle type (e.g., Two Wheelers, Three Wheelers) is ideal for long-term manufacturing based on sales trends and EV readiness.

Analyze sales patterns across Indian states from 2010 to 2025.

Use segmentation techniques to uncover dominant and emerging vehicle types.

Provide strategic recommendations for manufacturers entering the Indian vehicle or EV market.

# 📊 Datasets Used
## 1. india_vehicle_sales_yearly.xlsx
**State:** Indian state where the data was recorded.

**Year:** Sales year (2010–2025).

**Two Wheelers:** Total two-wheeler units sold.

**Three Wheelers:** Total three-wheeler units sold.

**Cars:** Total passenger cars sold.

**Buses:** Number of buses sold.

**Trucks:** Number of trucks sold.

## 2. EV_Dataset.csv
**Year:** Year of EV registration.

**Month Name:** Month of registration.

**Date:** Exact registration date.

**State:** Indian state of registration.

**Vehicle Class/Category/Type:** Classification and type of the EV.

**EV Sales Quantity:** Count of EVs registered.

# ⚙️ Methods & Techniques Used
**Exploratory Data Analysis (EDA):** Identified growth trends, demand patterns, and outliers.

**Time Series Forecasting:** Used ARIMA to model sales trends and forecast demand.

**Clustering:** Grouped vehicle sales patterns using KMeans for segment profiling.

**Growth Metrics:** Calculated Year-over-Year growth and indexed growth (base year: 2010).

# 🧠 Tools & Libraries
Python (Pandas, NumPy)

Seaborn & Matplotlib for visualization

Scikit-learn (KMeans, preprocessing)

Statsmodels (ARIMA)

Jupyter Notebook

# 📈 Key Insights
**Two Wheelers:** Dominated the market with ~159M units sold from 2010–2025; most consistent and scalable for mass manufacturing.

**Three Wheelers:** Showed steady growth; ideal for targeted manufacturing and EV transition (especially urban/shared mobility).

**Cars:** Volatile demand; not recommended without differentiation or innovation.

# ✅ Final Recommendation
**🥇 Manufacture Two Wheelers:** Highest demand and market penetration.

**🥈 Consider Three Wheelers:** Steady growth and future-fit for EV transformation.

**❌ Buses & Trucks:** Low or unstable volumes; not ideal for new manufacturing investment.

# 📁 Files Included
**Logu Prasanth - EV Market Segment Analysis.ipynb** – Analysis & visualizations

**india_vehicle_sales_yearly.xlsx** – Traditional vehicle sales dataset

**EV_Dataset.csv** – Electric vehicle registration dataset

# 🚀 How to Run
Clone this repository to your system.

Open the .ipynb file in Jupyter Notebook or VSCode.

Run all cells to explore data analysis and insights.

Review recommendations at the end of the notebook.

# 📌 Author
This project was completed individually as part of a market analysis task under internship guidelines.
