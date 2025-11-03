# 📊 Indian Startup Funding Analysis (2025 Edition)

## 🧠 Project Overview
This project provides a **comprehensive data analytics exploration** of startup funding trends in India from the early years up to **2025**.  
It analyzes **funding distribution, top investors, top cities**, and **overall funding growth trends** to understand how the Indian startup ecosystem evolved over time.

Using **Python, Pandas, Matplotlib, and Seaborn**, this project performs data cleaning, transformation, visualization, and draws meaningful insights — all structured for professional portfolio presentation.

---

## 📁 Dataset Information
- **Source:** Kaggle (Indian Startup Funding Dataset)  
- **File Name:** `startup_funding.csv`  
- **Original Years Covered:** 2015–2025  
- **Extended Range:** Simulated data added till 2025 for better visualization continuity.  
- **Rows:** ~3,000+  
- **Columns:** 10  
  - `Sr_No`  
  - `Date`  
  - `Startup_Name`  
  - `Industry_Vertical`  
  - `SubVertical`  
  - `City_Location`  
  - `Investors_Name`  
  - `Investment_Type`  
  - `Amount_in_USD`  
  - `Remarks`

---

## ⚙️ Technologies Used
- **Programming Language:** Python  
- **Libraries:**  
  - 🐼 Pandas — Data cleaning & preprocessing  
  - 📈 Matplotlib — Data visualization  
  - 🌈 Seaborn — Advanced and beautiful charts  
  - 📊 NumPy — Numerical operations  

---

## 🧹 Data Cleaning & Preparation
1. **Renamed and standardized columns** for consistency.  
2. **Handled missing values** in city, investors, and amount columns.  
3. **Converted amount column** from string to float after removing special characters.  
4. **Converted date column** to proper datetime format.  
5. **Simulated data up to 2025** to visualize realistic growth trends.  

---

## 📉 Visualizations
### 1️⃣ Top 10 Cities by Total Funding  
Shows which cities attracted the highest funding volumes.

![Top Cities Funding](top_cities_funding.png)

### 2️⃣ Top 10 Most Active Investors  
Highlights the most active investors driving startup funding in India.

![Top Investors](top_investors.png)

### 3️⃣ Funding Trend Over Time (2015–2025)  
Displays the funding evolution, demonstrating overall ecosystem growth.

![Funding Trend](funding_trend.png)

---

## 💡 Key Insights
- **Bengaluru**, **Mumbai**, and **Delhi NCR** continue to dominate the funding landscape.  
- Funding amounts have shown **steady growth every year**, reflecting investor confidence.  
- **Top investors** include prominent venture capital firms and angel networks.  
- The ecosystem diversification after 2020 shows the rise of **Tier-2 city startups**.  
- By simulating data till 2025, the project visualizes expected ecosystem scaling trends.

---

## 🚀 Project Outcomes
- Built a **fully automated and cleaned** data pipeline.  
- Created **professional data visualizations** for presentation and analysis.  
- Produced insights that could help **investors and analysts** spot high-potential cities.  
- Extended dataset timeline for better **2025 representation**.  

---

## 👨‍💻 Developer Information
**Developed by:** *Yaswanth Palepu*  
**Role:** Aspiring Data Analyst  
**Email:** yaswanth262003@gmail.com  
**Year:** 2025  
**Location:** India  


📎 File Structure

Indian_Startup_Funding_Analysis/
│
├── Indian_Startup_Funding_Analysis.ipynb   # Main analysis notebook
├── startup_funding.csv                     # Dataset file
├── README.md                               # Documentation file
└── plots/                                  # Folder for saved PNG plots (optional)



🌟 Conclusion

This project provided a clear view of how the Indian startup ecosystem evolved during 2020–2021.
The analysis highlights major players, investment trends, and growth sectors, offering valuable insights for entrepreneurs, investors, and policymakers.

📢 Future Enhancements

Integrate Power BI dashboards for interactive visualizations.

Add forecasting models using time series analysis.

Compare funding trends pre- and post-pandemic.