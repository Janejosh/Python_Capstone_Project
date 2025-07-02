# 🌾 Agricultural Yield & Farm Practice Analysis — Capstone Project

Welcome to the final capstone project of my data analysis internship! This project demonstrates my end-to-end data analysis skills applied to a real-world-style agriculture dataset. It includes data cleaning, feature engineering, insightful visualizations, and answers to key analytical questions — all powered by Python (Pandas, Seaborn, Matplotlib).

---

## 📁 Project Overview

- **Dataset**: A synthetic dataset simulating farm-level data from 4,500+ entries across different regions, crop types, and farming practices.
- **Goal**: Clean the dataset, perform deep exploratory data analysis (EDA), generate actionable insights, and simulate business-impacting metrics like yield categories and revenue.
- **Tools Used**: 
  - Python
  - Pandas, NumPy
  - Matplotlib, Seaborn
  - Folium (for geo-mapping)
  - Jupyter Notebook / VS Code

---

## 🧪 Key Columns in the Dataset

| Column              | Description                                        |
|---------------------|----------------------------------------------------|
| `Farm_ID`           | Unique identifier per farm                         |
| `Region`            | Geographic region (cleaned for consistency)        |
| `Crop_Type`         | Crop grown, including noisy text variants          |
| `Planting_Date`     | Date of planting                                   |
| `Harvest_Date`      | Date of harvesting                                 |
| `Area_ha`           | Area planted in hectares                           |
| `Yield_kg`          | Yield produced in kilograms                        |
| `Irrigation_Type`   | Type of irrigation used                            |
| `Soil_Type`         | Soil category used                                 |
| `Fertilizer_Used`   | Fertilizer category used                           |
| `Pesticide_Used`    | Pesticide category used                            |
| `Rainfall_mm`       | Rainfall in mm                                     |
| `Avg_Temperature_C` | Avg annual temperature                             |
| `Farmer_Age`        | Age of the farmer                                  |
| `Organic`           | Organic practice (Yes/No)                          |

---

## 🔧 Project Phases

### Phase 1: Data Loading & Inspection
- Inspected dataset structure and distributions.

### Phase 2: Column Standardization & Type Conversion
- Renamed to `snake_case` and converted datatypes.

### Phase 3: Categorical Cleanup
- Standardized text values in key categorical fields.

### Phase 4: Feature Engineering
- Derived: `yield_per_ha`, `growing_days`, `days_since_harvest`, and time-based fields.

### Phase 5: Missing Values & Outliers
- Replaced missing categories with `'Unknown'`.
- Analyzed outliers without dropping them to preserve data diversity.

### Phase 6: Export Clean Data
- Saved cleaned dataset to `cleaned_agri_data.csv`.

---

## 📊 Exploratory Data Analysis & Visualizations

Covered the following topics:

- **Regional & Crop Trends**
- **Yield Distribution & Time Trends**
- **Impact of Irrigation & Soil Types**
- **Fertilizer & Pesticide Usage Patterns**
- **Climate Influences**
- **Farmer Age Demographics**
- **Harvest Duration & Timing**
- **Certification Insights**
- **Revenue Simulation**
- **Geographic Mapping of Farms**

---

## 🧠 Insights & 📌 Recommendations

### Key Insights

- 🥇 **South region** had the highest number of farms and frequently ranked among the top in yield/ha.
- 🌱 **Wheat and Rice** were the most commonly cultivated crops, but **Barley** and **Soybean** showed higher yield efficiency per hectare.
- 💧 **Drip irrigation** was linked with the highest yield/ha, while **Flood** and **None** had poor performance — though some farms still performed well with these, depending on soil and fertilizer use.
- 🌡️ Yield had a **positive correlation** with moderate rainfall and optimal average temperatures (~23–28°C).
- 🧓 Younger and middle-aged farmers (25–45) were more likely to use organic methods and had slightly higher yield efficiency.
- 📅 Peak planting months were **May–July**, with yield showing **seasonal fluctuations**.

### Recommendations

- ✅ Encourage farmers in underperforming regions to adopt practices from high-yielding regions (e.g., crop type + irrigation + soil prep).
- ✅ Train farmers on **Drip and Sprinkler irrigation** systems to optimize water usage and improve yields.
- ✅ Promote and subsidize **organic-certified fertilizers and pesticides**, especially in high-performing areas.
- ✅ Invest in **weather-smart farming practices** to mitigate climate impact on yields.
- ✅ Provide targeted support to **older farmers** through digital and field-based advisory tools to encourage adoption of modern practices.
- ✅ Explore **market linkage programs** based on simulated `revenue_estimate` to improve farmer incomes.

---

## 📁 File Structure

