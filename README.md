# 🌾 Seasonal Agriculture Performance Analysis

## 📌 Project Overview

Seasonal Agriculture Performance Analysis is a data-driven project that analyzes agricultural performance across **Kharif, Rabi, and Zaid** seasons.

The project explores how seasonal conditions, crop selection, resource utilization, irrigation methods, and economic factors are associated with agricultural productivity and profitability.

Using Python-based data analysis and visualization techniques, the project identifies meaningful patterns and relationships in the agricultural dataset and provides evidence-based recommendations for better seasonal farming planning.

## 🎯 Objectives

- Analyze agricultural performance across different seasons.
- Compare crop yield and production across seasons and crops.
- Analyze seasonal profitability and economic performance.
- Study rainfall, temperature, humidity, soil moisture, and other environmental factors.
- Analyze fertilizer, nutrient, pesticide, and water usage.
- Compare different irrigation methods.
- Investigate relationships between resource utilization and crop yield.
- Identify high-performing and low-performing crop-season combinations.
- Generate data-driven recommendations for agricultural planning.

## 📊 Dataset

The dataset contains **4,000 agricultural records and 28 variables** covering:

- Farm and crop information
- Environmental conditions
- Soil characteristics
- Nutrient and fertilizer usage
- Irrigation methods
- Water usage and efficiency
- Crop yield and production
- Market price, cost, revenue, and profit
- Disease and pest risk

## 🛠️ Technologies Used

**Programming Language:** Python

**Libraries:**
- Pandas
- NumPy
- Matplotlib
- Seaborn

**Environment:** Jupyter Notebook

**Techniques:**
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Descriptive Statistics
- Grouped Analysis
- Correlation Analysis
- Data Visualization
- Outlier Analysis

## 🔄 Project Workflow

```text
Raw Dataset
     ↓
Data Loading
     ↓
Data Understanding
     ↓
Data Cleaning & Preprocessing
     ↓
Exploratory Data Analysis
     ↓
Seasonal Performance Analysis
     ↓
Crop-Level Analysis
     ↓
Environmental Analysis
     ↓
Resource Usage Analysis
     ↓
Irrigation Analysis
     ↓
Correlation Analysis
     ↓
Visualization
     ↓
Key Findings
     ↓
Recommendations
```

## 🧹 Data Cleaning

The dataset was checked for missing values, duplicate records, data consistency, and outliers.

### Missing Value Treatment

- **Rainfall:** Season-wise median imputation
- **Soil Moisture:** Season-wise median imputation
- **Yield:** Reconstructed using production and farm area where applicable

No duplicate rows were found.

Yield outliers were investigated at the crop level. Most apparent high-yield outliers were associated with **Sugarcane**, which has a much higher yield scale than the other crops. These observations were retained because they were not treated as data-entry errors.

## 📊 Key Findings

### 🌾 Seasonal Performance

Average yield:

- **Kharif:** 5.63 tonnes/ha
- **Rabi:** 5.09 tonnes/ha
- **Zaid:** 4.63 tonnes/ha

Kharif recorded the highest average profit of approximately **₹1.79 lakh**, while Zaid recorded a negative average profit of approximately **₹24,805**.

### 💰 Crop Profitability

| Crop | Average Profit |
|------|---------------:|
| Sugarcane | ₹8.17 lakh |
| Chilli | ₹7.51 lakh |
| Cotton | ₹1.25 lakh |
| Groundnut | ₹44,858 |
| Pulses | -₹4,238 |
| Maize | -₹83,978 |
| Rice | -₹1.02 lakh |
| Wheat | -₹1.23 lakh |

Sugarcane and Chilli showed particularly strong economic performance.

### 💧 Water Efficiency

Water-use efficiency showed a **very strong positive correlation with yield**:

**r = 0.92**

This indicates that farms with higher water-use efficiency tend to have higher yield in the analyzed dataset.

### 🚜 Irrigation Analysis

- **Kharif:** Drip recorded the highest average yield.
- **Rabi:** Drip recorded the highest average yield.
- **Zaid:** Sprinkler recorded the highest average yield.

This indicates that irrigation effectiveness varies across seasons.

### 🌱 Resource Relationships

Fertilizer and nutrient variables showed very weak individual linear correlations with yield. Therefore, simply increasing resource quantity cannot be assumed to improve yield based on this analysis.

## 📈 Visualizations

The project includes:

- Average Yield by Season
- Average Profit by Season
- Average Profit by Crop
- Water Efficiency vs Yield
- Average Yield by Irrigation Method and Season
- Correlation Heatmap

## 💡 Recommendations

1. Improve water-use efficiency rather than focusing only on increasing water consumption.
2. Consider efficient irrigation methods such as drip where appropriate.
3. Evaluate sprinkler irrigation for suitable Zaid cultivation.
4. Use crop-season profitability analysis for better crop selection.
5. Identify high-resource and low-profit combinations before cultivation.
6. Support seasonal farming decisions using historical agricultural data.
7. Consider both productivity and profitability when planning crop cultivation.

## 🚀 Future Scope

- Develop machine learning models for yield prediction.
- Develop crop profitability prediction models.
- Build a crop recommendation system.
- Integrate real-time weather data.
- Integrate soil sensor data.
- Add market-price forecasting.
- Develop an interactive agricultural dashboard.
- Expand the dataset to multiple years and regions.

## 📂 Project Structure

```text
seasonal-agriculture-performance-analysis/
│
├── dataset/
│   └── seasonal_agriculture_performance_dataset.csv
│
├── Seasonal_Agriculture_Performance_Analysis.ipynb
│
├── visualizations/
│   ├── average_yield_by_season.png
│   ├── average_profit_by_season.png
│   ├── average_profit_by_crop.png
│   ├── water_efficiency_vs_yield.png
│   ├── irrigation_yield_analysis.png
│   └── correlation_heatmap.png
│
└── README.md
```

## 👩‍💻 Project Author

**Jahnavi Samala**

B.Tech – Computer Science Engineering  
Sridevi Women's Engineering College

## 📜 Project Context

This project was developed as part of the **VOIS AICTE Major Project – 2026–2027**.

## ⭐ Conclusion

The analysis demonstrates that agricultural performance varies considerably across seasons and crops. Kharif showed the strongest overall performance, while Zaid showed weaker profitability and water-use efficiency. Crop selection and resource efficiency play important roles in agricultural performance, with water-use efficiency showing a particularly strong association with yield.

The project demonstrates how data analysis and visualization can support more informed and evidence-based agricultural planning.
