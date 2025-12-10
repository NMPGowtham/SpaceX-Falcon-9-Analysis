# 🚀 SpaceX Falcon 9 Launch & Landing Analysis
### Data Wrangling • SQL EDA • Visualization • Machine Learning • Dash Dashboard

---

## 📌 Overview
This project analyzes **SpaceX Falcon 9 rocket launches** to understand the key factors affecting landing success.  
Data is sourced from:

- **SpaceX REST API**
- **Wikipedia web scraping**

The workflow includes data wrangling, SQL-based EDA, visual analytics, supervised ML prediction, and an interactive dashboard using **Dash**.

---

## 🛰️ Objectives
- Perform data cleaning and preprocessing  
- Explore the dataset using Pandas and SQL  
- Visualize payload, orbit, launch sites, and success patterns  
- Predict landing success using ML models  
- Build an interactive dashboard with Plotly Dash  
- Evaluate model performance using confusion matrix and accuracy  

---

## 📂 Dataset Description

The dataset contains the following fields:

FlightNumber, Date, BoosterVersion, PayloadMass, Orbit, LaunchSite,
Outcome, Flights, GridFins, Reused, Legs, LandingPad, Block,
ReusedCount, Serial, Longitude, Latitude, Class

Where:
- `Class = 1 → Successful landing`
- `Class = 0 → Failed landing`

---

## 🔧 Technologies Used
- Python  
- Pandas, NumPy  
- SQL (SQLite / Jupyter SQL Magic)  
- Seaborn, Matplotlib, Plotly  
- Scikit-Learn  
- Dash Framework  

