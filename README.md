# ✈️ Flight Fare Prediction Using Machine Learning

**Developed by Rakshitha Thogaru | B.Tech Computer Science and Engineering | 2026 Graduate**

## 📌 About the Project

Flight Fare Prediction is a Machine Learning project developed to analyze historical flight ticket data and predict flight prices based on different flight-related features.

The project demonstrates an end-to-end Machine Learning workflow, including data analysis, preprocessing, feature engineering, model development, evaluation, and model comparison.

## 🎯 Project Objectives

- Analyze historical flight fare data.
- Identify patterns and factors influencing flight prices.
- Perform data cleaning and feature engineering.
- Develop and compare multiple Machine Learning regression models.
- Select the best-performing model based on evaluation metrics.

## 📊 Dataset Information

- Original Records: 10,683
- Original Features: 11
- Target Variable: Price
- Dataset Period: March–June 2019

**Features include:** Airline, Date of Journey, Source, Destination, Route, Departure Time, Arrival Time, Duration, Total Stops, and Additional Information.

## 🛠️ Technologies & Tools

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
- Joblib

## 🔄 Project Workflow

1. Data Loading and Exploration
2. Data Cleaning and Preprocessing
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. Train-Test Split
6. Machine Learning Model Development
7. Model Evaluation and Comparison
8. Best Model Selection and Saving

## 🤖 Machine Learning Algorithms

- Linear Regression
- Decision Tree Regressor
- Gradient Boosting Regressor
- Random Forest Regressor

## 📈 Model Performance Comparison

| Model | MAE (₹) | RMSE (₹) | R² Score |
|---|---:|---:|---:|
| Random Forest | 642.02 | 1349.72 | 0.9119 |
| Decision Tree | 871.80 | 1736.92 | 0.8542 |
| Gradient Boosting | 1277.16 | 1936.12 | 0.8188 |
| Linear Regression | 1542.86 | 2362.97 | 0.7301 |

## 🏆 Best Performing Model

**Random Forest Regressor**

- MAE: ₹642.02
- RMSE: ₹1,349.72
- R² Score: 0.9119
- Cross-Validation MAE: ₹697.68
- Cross-Validation R²: 0.8774

Random Forest achieved the best performance among the four evaluated models. The trained model pipeline was saved using Joblib.

## 💡 Key Findings

- Random Forest achieved the highest R² score.
- Feature engineering helped prepare the dataset for predictive modelling.
- Approximately 82.51% of test predictions were within ₹1,000 of the actual prices.
- Model comparison helped identify the most suitable algorithm among those evaluated.

## ⚠️ Project Limitations

- The dataset contains historical flight information from 2019.
- Real-time airline pricing and booking lead-time information are not available.
- The model predicts based on historical patterns and is not a live flight-price forecasting system.
- Further validation with recent flight data is required before production deployment.

## 📁 Project Files

- `FlightFarePrediction.ipynb` – Complete analysis, model development, and evaluation.
- `Flight_Fare.xlsx` – Flight fare dataset.
- `outputs/models/flight_fare_random_forest.pkl` – Saved trained model (maintained in the local project folder).

## 👩‍💻 About the Developer

**Rakshitha Thogaru**

B.Tech Graduate in Computer Science and Engineering | 2026

Aspiring Data Scientist | AI/ML Engineer | Data Analyst

**GitHub Username:** @RakshithaThogaru

**GitHub Profile:** https://github.com/RakshithaThogaru

