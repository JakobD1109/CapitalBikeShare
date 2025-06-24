# Attention: 

Please find the full project presentation under the following link: 
https://docs.google.com/presentation/d/12FbS4XW0BC7a-OL2aAm9Ik-hcHZh8PC6fDUE7sXil-Y/edit?usp=sharing

Please download a dataset too large for GitHub but relevant to run the code under the following link: 
https://drive.google.com/file/d/1BvHmY1bdqJzhMu7bNaG5Um7dn3tu1aC8/view?usp=drive_link

# 🚲 Capital BikeShare Dynamics

**A Data-Driven Analysis of Bike Distribution and Redistribution Optimization within Washington DC’s Bikesharing Ecosystem**  
**Author:** Jakob Drews  
**Cohort:** Code Academy Berlin – Data Science (March 2025)

---

## 📊 Project Summary

This project explores **spatial imbalances** in Washington DC’s Capital BikeShare system. It combines **descriptive analytics**, **predictive modeling**, and **geospatial optimization** to:

- Measure station-level system imbalance with a custom metric
- Predict ride demand at the station level
- Recommend practical redistribution strategies — all **without adding more bikes**

---

## 🧩 Data Sources

- **Capital BikeShare (2023 full year):** Trip-level CSV data  
- **Weather data:** Hourly/daily features (temperature, wind, humidity)  
- **Geospatial data:** Elevation & ward boundaries (GeoJSON)

---

## 📌 Features Used

- **Location-based:** e.g. Station ID, coordinates, ward  
- **Temporal:** e.g. Date, day of week, hour, season, holiday  
- **Ride metadata:** e.g. Bike type, trip duration/distance  
- **User type:** e.g. Member vs. casual  
- **Station context:** e.g. Elevation, density, popularity  
- **Weather:** e.g. Real-feel temperature, wind speed, rain  

➡️ **43 unique variables** used across the modeling and analysis pipeline.

---

## 🔧 Methodology

### 1. 🚦 Imbalance KPI: **TANF**  
Total Absolut Net Flow — a custom metric representing the **minimum number of bikes to move** 
to equalize supply and demand across wards or stations.

### 2. 🤖 Machine Learning  
- **XGBoost** used to predict daily rides per station  
- Cross-validated across 4 seasonal splits  
- **Avg. R² = 0.82**  
- 95% of stations predicted within ±5 rides

### 3. 🧭 Spatial Flow Analysis  
- Ward-level **net inflows and outflows** tracked  
- Sankey diagrams used to visualize directional flow imbalances (e.g., from Ward 1 to Ward 6)

### 4. 🔄 Redistribution Strategy  
- **Intraward**: User incentives to rebalance locally  
- **Interward**: Route optimization between surplus and deficit zones  
- **Routing**: Based on geodistance between stations

---

## 📈 Key Results

- Ward 6 is a (the only) net inflow neighboorhood
- Several stations have persistent deficit or surplus  
- Predictive model effectively forecasts demand  
- Proposal of logistic bike redistribution scheme taking 
  into account level of surplus/deficit and distance btw stations

---

## 🖼️ Interactive Visualizations

- **Sankey Diagram (Ward Flows):**  
  👉 [View Online](https://jakobd1109.github.io/sankey_ward_bike_flows.html)

- **Net Bike Flow Map:**  
  👉 [View Online](https://jakobd1109.github.io/citywide_net_bikeflow_variable_threshold.html)

- **ML Prediction Residuals:**  
  👉 [View Online](https://jakobd1109.github.io/ML_residuals_over_the_year.html)

---

## 📬 Contact

Feel free to reach out via GitHub for feedback or collaboration ideas.

