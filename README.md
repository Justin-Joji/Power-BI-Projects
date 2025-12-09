# Power-BI-Projects
Collection of Power BI dashboards and analytics projects focused on business and sales insights.

## 1 . Tata Cars Sales Dashboard
📊 Project Overview

This project analyzes Tata Motors car sales data (2000–2025) for both new and used vehicles using Power BI.
The aim is to understand sales trends, best-selling models, fuel preferences, body type performance, transmission usage, EV growth, and state-wise sales insights.

⸻

🎯 Objectives
	•	Identify best-selling models (overall & by body type)

	•	Compare new vs used car sales
	•	Analyze demand across fuel types (Petrol, Diesel, CNG, Electric, Hybrid)
	•	Study EV penetration
	•	Evaluate transmission preferences
	•	Find top-performing states
	•	Highlight mileage leaders
	•	Perform data cleaning & correction for fuel types and body types

⸻

🧹 Data Preparation

Raw dataset had multiple inconsistencies:

	•	Incorrect fuel type tagging (some Petrol/Diesel cars marked as EV)
	•	Body type mismatches
	•	Duplicate model naming formats

✅ Corrections Done:

	•	Created Corrected Fuel Type column:
	•	Cars containing “EV” in model → marked Electric
	•	Incorrect Electric entries → reverted to Petrol
	•	Diesel & CNG preserved
	•	Hybrid & Petrol+CNG retained
	•	Created Corrected Body Type
	•	Standardized model names
	•	Filtered new vs used using owner count

⸻

📁 Dataset Summary

	•	Time span: 2000 – 2025
	•	Rows: ~100,000+ sales records
	•	Car models: 18
	•	States: All major Indian states
	•	Sales types: New & Used vehicles

⸻

📌 Dashboards Built

🔹 Dashboard  – Sales Overview

	•	Total Sales Units
	•	New vs Used vehicle split
	•	Year-wise sales trend
	•	State-wise performance
 • Segment Analysis
	•	Best Selling:
	•	Sedan
	•	Hatchback
	•	SUV
	•	Fuel-wise sales
	•	Transmission-wise sales
	•	Mileage comparison
 • EV & Regional Insights
	•	Total EV sales (New & Used)
	•	EV growth trend
	•	Top EV models
	•	State-wise EV distribution
 • Sales by transmission
 • Region Sales

⸻

⸻

📈 Key Findings

	•	🚘 Punch is the overall best-selling model and top mileage performer.
	•	🌍 Tamil Nadu leads total sales among all states.
	•	🚗 Used car demand is highest for Hatchbacks.
	•	🚙 Sedans have the lowest overall demand, mostly limited to the Tigor.
	•	⚡ EV adoption remains low:
	•	New EV units: ~6,576
	•	Used EV units: ~26,765
	•	⛽ Petrol dominates the fuel segment.
	•	🔁 Diesel and CNG show niche demand.
	•	⚡ Electric vehicles remain a niche segment at this stage.
	•	⚙️ Manual transmission remains dominant over automatic.
	•	📅 Year 2000 recorded the highest overall sales volume.

⸻

⸻

✅ Business Recommendations

	•	🔧 Increase production & promotion of Punch, due to strong sales & mileage leadership.
	•	🗺️ Focus marketing campaigns in Tamil Nadu, the highest-performing state.
	•	🚘 Boost Sedan segment visibility, especially beyond the Tigor model.
	•	⚡ Invest in EV incentives & awareness programs to drive higher adoption.
	•	⛽ Continue petrol model availability while maintaining Diesel & CNG for niche markets.
	•	🔁 Expand Automatic transmission options to match growing market preference.
	•	🛠️ Increase availability of hatchbacks in used car markets where demand is strong.

⸻

⸻

🛠 Tools & Technologies Used

	•	Power BI
	•	Power Query for Data Cleaning
	•	DAX for Measures & Calculations
	•	Microsoft Excel – Dataset preparation
	•	GitHub – Project hosting & documentation

⸻

⸻

✅ Key DAX Functions Used

	•	CALCULATE() – Apply dynamic filters
	•	FILTER() – Row selection based on conditions
	•	SELECTEDVALUE() – Fetch single slicer value
	•	TOPN() – Identify best-selling models
	•	SUM() – Total sales volumes
	•	RANKX() – Ranking car models & states

⸻

⸻

📂 Repository Contents

	•	Power BI dashboard screenshots
	•	Dataset ZIP file
	•	PPT presentation slides
	•	This README documentation

⸻

⸻

👤 Author

Justin
📊 Data Analyst
💡 Portfolio: Power BI Sales Analytics Projects.
