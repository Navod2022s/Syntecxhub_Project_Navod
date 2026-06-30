# 🏡 California Housing Price Prediction
## 📌 Project Overview

This project builds machine learning models to predict median house prices in California using demographic and geographic data.

The workflow includes:

* Exploratory Data Analysis (EDA)
* Feature engineering
* Regression modeling
* Model comparison
* Hyperparameter tuning
  
## 📊 Dataset
* California Housing Dataset
* Features: income, location, population, housing stats
* Target: median house value
  
## 🧠 Problem Type

* Regression (predict continuous value)

## 🔧 Feature Engineering

* Created additional features:

  * rooms_per_household
  * bedrooms_per_room
  * population_per_household
  * 🤖 Models Used
  * Linear Regression
  * Decision Tree Regressor
  * Random Forest Regressor
  * Tuned Random Forest (GridSearchCV)
  
## 📈 Model Performance
| Model               |     R² |   RMSE |
| ------------------- | -----: | -----: |
| Linear Regression   | 0.6254 |  70060 |
| Decision Tree       | 0.6287 |  69755 |
| Random Forest       | 0.8165 |  49038 |
| Tuned Random Forest | 0.8194 | ~48500 |

## 📊 Key Insights
* Median income is the strongest predictor of house prices
* Coastal locations tend to have higher prices
* Random Forest significantly outperforms linear models
## 📉 Visualizations
 * Model Comparison
 * Feature Importance
 * Actual vs Predicted

## Feature Importance


## 🚀 Final Model

* Best model:

   * Random Forest Regressor (Tuned)
   * CV R² ≈ 0.819
## 📌 Technologies Used
* Python
* Pandas, NumPy
* Scikit-learn
* Matplotlib, Seaborn
## 🔮 Future Improvements
* XGBoost / LightGBM
* Geospatial clustering
* Deployment as web API
* Streamlit dashboard
