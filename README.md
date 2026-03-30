# Algerian-forest
Machine Learning project predicting Fire Weather Index (FWI) using meteorological data with EDA, feature analysis, and regression models (Ridge, Lasso, ElasticNet).

# 🔥 Algerian Forest Fires Prediction (ML Project)

This project focuses on analyzing and predicting wildfire behavior using meteorological data from the Algerian Forest Fires dataset. The goal is to understand how environmental factors influence fire intensity and to build regression models to predict the Fire Weather Index (FWI).

---

## 📊 Dataset Overview

- Total instances: 244  
- Regions: Bejaia (Northeast Algeria) and Sidi Bel-abbes (Northwest Algeria)  
- Time period: June 2012 – September 2012  

### Features include:
- Temperature  
- Relative Humidity (RH)  
- Wind Speed (Ws)  
- Rain  
- FFMC, DMC, DC (fuel moisture indicators)  
- ISI, BUI  
- Fire Weather Index (FWI)  

---

## 🎯 Objective

- Perform Exploratory Data Analysis (EDA) to uncover patterns  
- Understand relationships between environmental variables  
- Build regression models to predict **FWI (Fire Weather Index)**  
- Compare model performance and select the best approach  

---

## 🔍 Exploratory Data Analysis

Key observations:
- Fire activity peaks during **July–August**, indicating strong seasonal influence  
- **Temperature and dryness indicators** show positive correlation with fire intensity  
- **Relative humidity** is negatively correlated with fire occurrence  
- Strong multicollinearity observed among FWI components (ISI, BUI, DMC, DC)

---

## ⚙️ Data Preprocessing

- Converted object-type columns to numeric values  
- Handled missing/inconsistent data  
- Encoded target labels where necessary  
- Applied feature scaling for model training  

---

## 🤖 Models Used

- Lasso Regression  
- Ridge Regression  
- ElasticNet Regression  

---

## 📈 Model Performance

| Model        | MAE   | R² Score |
|-------------|------|--------|
| Lasso        | ~0.56 | ~0.98 |
| Ridge        | ~0.56 | ~0.98 |
| ElasticNet   | ~1.88 | ~0.87 |

✅ **Ridge Regression performed best**, likely due to its ability to handle multicollinearity among features.

---

## 📊 Visualizations

The project includes:
- Distribution plots for all features  
- Correlation heatmaps  
- Boxplots for outlier detection  
- Monthly fire analysis  
- Prediction vs actual comparison plots  

---

## 🛠️ Tech Stack

- Python  
- NumPy, Pandas  
- Matplotlib, Seaborn  
- Scikit-learn  

---

## 📁 Project Structure
