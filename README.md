# 🧠 House Price Prediction using Random Forest

This project was developed as part of my Master’s Final Project (Non-Thesis).  
The aim is to predict housing prices using feature engineering and a Random Forest regression model.

## 📊 Project Summary
- **Language:** Python  
- **Libraries:** pandas, numpy, matplotlib, seaborn, scikit-learn  
- **Model:** Random Forest Regressor  
- **Preprocessing:** IQR outlier removal, One-Hot Encoding, Feature Engineering  
- **Evaluation:** Hold-out and 5-fold Cross-Validation  
- **Metrics:**  
  - R² (Test): 0.636  
  - Mean CV R²: 0.609  

## ⚙️ Feature Engineering
- `total_rooms` = bedrooms + bathrooms  
- `area_bed_bath` = area / (bedrooms + bathrooms)

## 🖼️ Visuals (to be added)
- 📈 Boxplot of price  
- 📊 Feature importance chart  
- 📉 Predicted vs Actual scatterplot
