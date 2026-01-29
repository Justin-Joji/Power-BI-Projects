# Power-BI-Projects
Collection of Power BI dashboards and analytics projects focused on business and sales insights.

# 1 . Tata Cars Sales Dashboard
## 📊 Overview
This project analyzes Tata Motors car sales data (2000–2025) for both new and used vehicles using Power BI. The aim is to understand sales trends, best-selling models, fuel preferences, body type performance, transmission usage, EV growth, and state-wise sales insights.

## 🎯 Objectives
- Identify best-selling models (overall & by body type)
- Compare new vs used car sales
- Analyze demand across fuel types (Petrol, Diesel, CNG, Electric, Hybrid)
- Study EV penetration
- Evaluate transmission preferences
- Find top-performing states
- Highlight mileage leaders
- Perform data cleaning & correction for fuel types and body types

## 🧹 Data Preparation
Raw dataset had multiple inconsistencies:
- Incorrect fuel type tagging (some Petrol/Diesel cars marked as EV)
- Body type mismatches
- Duplicate model naming formats

## ✅ Corrections
- Created Corrected Fuel Type column:
- Cars containing “EV” in model → marked Electric
- Incorrect Electric entries → reverted to Petrol
- Diesel & CNG preserved
- Hybrid & Petrol+CNG retained
- Created Corrected Body Type
- Standardized model names
- Filtered new vs used using owner count

## 📁 Dataset Summary
- Time span: 2000 – 2025
- Rows: ~100,000+ sales records
- Car models: 18
- States: All major Indian states
- Sales types: New & Used vehicles

## 📌 Dashboards Built
### 🔹Dashboard  – Sales Overview
  - Total Sales Units
  - New vs Used vehicle split
  - Year-wise sales trend
  - State-wise performance
  
### 🔹Segment Analysis
  - Best Selling:
  - Sedan
  - Hatchback
  - SUV
  - Fuel-wise sales
  - Transmission-wise sales
  - Mileage comparison
  
### 🔹EV & Regional Insights
  - Total EV sales (New & Used)
  - EV growth trend
  - Top EV models
  - State-wise EV distribution
  
### 🔹Sales by transmission

### 🔹Region Sales

## 📈 Key Findings
- 🚘 Punch is the overall best-selling model and top mileage performer.
- 🌍 Tamil Nadu leads total sales among all states.
- 🚗 Used car demand is highest for Hatchbacks.
- 🚙 Sedans have the lowest overall demand, mostly limited to the Tigor.
- ⚡ EV adoption remains low:
  - New EV units: ~6,576
  - Used EV units: ~26,765
- ⛽ Petrol dominates the fuel segment.
- 🔁 Diesel and CNG show niche demand.
- ⚡ Electric vehicles remain a niche segment at this stage.
- ⚙️ Manual transmission remains dominant over automatic.
- 📅 Year 2000 recorded the highest overall sales volume.

## ✅ Business Recommendations
- 🔧 Increase production & promotion of Punch, due to strong sales & mileage leadership.
- 🗺️ Focus marketing campaigns in Tamil Nadu, the highest-performing state.
- 🚘 Boost Sedan segment visibility, especially beyond the Tigor model.
- ⚡ Invest in EV incentives & awareness programs to drive higher adoption.
- ⛽ Continue petrol model availability while maintaining Diesel & CNG for niche markets.
- 🔁 Expand Automatic transmission options to match growing market preference.
- 🛠️ Increase availability of hatchbacks in used car markets where demand is strong.

## 🛠 Tools & Technologies Used
- Power BI
- Power Query for Data Cleaning
- DAX for Measures & Calculations
- Microsoft Excel – Dataset preparation
- GitHub – Project hosting & documentation

## ✅ Key DAX Functions Used
- CALCULATE() – Apply dynamic filters
- FILTER() – Row selection based on conditions
- SELECTEDVALUE() – Fetch single slicer value
- TOPN() – Identify best-selling models
- SUM() – Total sales volumes
- AVG() - For getting average
- SUMMARIZE() - Group data and create a summary table
- MAXX() - Find the maximum value
- RANKX() – Ranking car models & states

## 📂 Repository Contents
- Power BI dashboard screenshots
- Dataset ZIP file
- PPT presentation slides
- This README documentation

## 📂 Project Files Included
This repository contains all files related to the Power BI project.

## 📊 1. Project Presentation (PPT)
- **projectpresentationtata.pptx** [projectpresentationtata.pptx](https://github.com/Justin-Joji/Power-BI-Projects/blob/main/projectpresentationtata.pptx)
  Contains the full project explanation,dashboard walkthrough,key insights and conclusions.

### ✅ 2. Dashboard Screenshots
The following images show key views from the Power BI dashboard:
- [Screenshot 2025-12-08 144558.png](https://github.com/Justin-Joji/Power-BI-Projects/blob/main/Screenshot%202025-12-08%20144558.png)
- [Screenshot 2025-12-08 144620.png](https://github.com/Justin-Joji/Power-BI-Projects/blob/main/Screenshot%202025-12-08%20144620.png)
- [Screenshot 2025-12-08 144636.png](https://github.com/Justin-Joji/Power-BI-Projects/blob/main/Screenshot%202025-12-08%20144636.png)
- [Screenshot 2025-12-08 144649.png](https://github.com/Justin-Joji/Power-BI-Projects/blob/main/Screenshot%202025-12-08%20144649.png)
- [Screenshot 2025-12-08 144710.png](https://github.com/Justin-Joji/Power-BI-Projects/blob/main/Screenshot%202025-12-08%20144710.png)
- [Screenshot 2025-12-08 144730.png](https://github.com/Justin-Joji/Power-BI-Projects/blob/main/Screenshot%202025-12-08%20144730.png)

### 📅 3. Dataset
- **tata_cars_100k.zip** [ tata_cars_100k.zip](https://github.com/Justin-Joji/Power-BI-Projects/blob/main/tata_cars-100k.zip)
  This ZIP file contains the orginal dataset used for building all visualizations in Power BI.

## How to Use These Files
- Download the **presentation** to view the project summary.
- View **screenshots** for a quick overveiw of the dashboards.
- Extract the **dataset ZIP** to load into Power BI.
  
# 👤 Author
### Justin  
📊 Data Analyst  
💡 Portfolio: Power BI Sales Analytics Projects.





# 📊 ABB India Stock Performance Analysis (2000–2025)

This project presents an end-to-end **stock performance analysis of ABB India** using **Power BI**, covering historical data from **2000 to 2025**.  
The dashboard focuses on **price trends, trading volume, volatility, and long-term performance insights**.

---

## 🧾 Project Overview

The objective of this project is to analyze ABB India’s historical stock data to understand:

- Long-term price growth
- Trading volume behavior
- Year-end performance trends
- Market volatility through daily price range
- Relationship between price movement and volume

This dashboard is designed for **data analysis portfolios, interviews, and business intelligence demonstrations**.

---

## 🗂 Dataset Details

- **Time Period:** 2000 – 2025  
- **Granularity:** Daily stock data aggregated to yearly level  
- **Key Columns Used:**
  - Date
  - Open Price
  - High Price
  - Low Price
  - Close Price
  - Volume

---

## 📈 KPIs Included

- **Latest Close Price**
- **Highest Price (All Time)**
- **Lowest Price (All Time)**
- **Total Trading Volume**
- **Average Trading Volume**
- **Average Daily Range**
- **Year-End Closing Price**

---

## 📊 Dashboard Visuals

### 1️⃣ Year-End Closing Price Trend (2000–2025)
- Shows long-term price growth
- Highlights major breakout periods and corrections

### 2️⃣ Trading Volume Trend
- Identifies periods of high investor activity
- Helps relate volume spikes with price movements

### 3️⃣ Price vs Volume Analysis (Combo Chart)
- Compares **Year-End Close** with **Total Trading Volume**
- Useful for understanding accumulation and distribution phases

### 4️⃣ Average Close Price by Year
- Horizontal bar chart for easy year-wise comparison
- Highlights recent price acceleration

### 5️⃣ Daily Range by Year
- Measures yearly volatility
- Identifies high-risk and stable periods

---

## 🛠 Tools & Technologies Used

- **Power BI Desktop**
- **DAX (Data Analysis Expressions)**
- **Power Query**
- **Data Modeling**
- **Custom Measures & KPIs**

---

## 🧠 Key Insights

- ABB India shows **strong long-term growth**, especially post-2020.
- Trading volume spikes align with major price breakouts.
- Volatility was significantly higher in early years compared to recent periods.
- Recent years indicate **price appreciation with stable volume**, suggesting strong investor confidence.

---

## 📁 Repository Structure
- Power BI dashboard screenshots
- Dataset ZIP file
- This README documentation

---
## 📂 Project Files Included
This repository contains all files related to the Power BI project.

### ✅ 2. Dashboard Screenshots
The following images show key views from the Power BI dashboard:



---

## 🚀 How to Use

1. Download the `.pbix` file
2. Open in **Power BI Desktop**
3. Refresh data if required
4. Interact using slicers and visuals

---

## 🔮 Future Enhancements

- Add moving averages (50 DMA, 200 DMA)
- Forecast future prices using time-series analysis
- Compare ABB India with NIFTY or peer stocks
- Add return % and CAGR analysis

---

## 👤 Author

**Justin**  
Data Analyst | Power BI | Data Visualization  

📌 *This project is created for learning, portfolio, and analytical demonstration purposes.*

---

⭐ If you like this project, don’t forget to **star the repository**!
