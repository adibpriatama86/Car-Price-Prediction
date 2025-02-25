# Car Price Prediction

## Overview
This project aims to predict car prices using machine learning techniques. The dataset contains information about various car brands, models, and features. The goal is to build a model that accurately estimates the price of a car based on its attributes.

## Dataset
The dataset used in this project is sourced from [Kaggle](https://www.kaggle.com/datasets/asinow/car-price-dataset) and includes the following columns:

- **Brand**: Car manufacturer (e.g., Toyota, Honda, BMW)
- **Model**: Specific car model
- **Year**: Manufacturing year
- **Engine_Size**: Engine capacity in liters
- **Fuel_Type**: Type of fuel used (Petrol, Diesel, etc.)
- **Transmission**: Type of transmission (Manual, Automatic)
- **Mileage**: Total distance the car has traveled
- **Doors**: Number of doors in the car
- **Owner_Count**: Number of previous owners
- **Price**: The target variable (car price in currency unit)

## Steps
1. **Data Preparation**
   - Handling missing values
   - Data cleaning & feature selection
2. **Exploratory Data Analysis (EDA)**
   - Visualizing price distribution
   - Correlation heatmap
3. **Model Training**
   - Implemented **Linear Regression** and **Random Forest** models
   - Splitting data into training & testing sets
4. **Evaluation**
   - Used **Mean Squared Error (MSE)** and **R² Score** to assess performance

## Results
- **Linear Regression**: R² Score = **0.9995**, MSE = **4213.92**
- **Random Forest**: R² Score = **0.9679**, MSE = **294827.40**
- Linear Regression achieved a near-perfect R² score, but this might indicate overfitting.
- Random Forest performed well but had a higher MSE, suggesting it could benefit from hyperparameter tuning.

## Visualizations
- **Price Distribution**
- **Correlation Heatmap**
- **Feature Importance (Random Forest)**
- **Actual vs Predicted Prices**

## Requirements
To run this project, you need:
- **Python 3.x**
- Libraries: `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`

## How to Run
1. **Clone this repository**:
   ```bash
   git clone https://github.com/adibpriatama86/Car_Price_Prediction.git
   ```
2. **Open the Jupyter Notebook or Google Colab**:
   - Jupyter Notebook: `car_price_prediction.ipynb`
   - Google Colab: [Colab Link](https://colab.research.google.com/drive/1FetYxk20kqxsh44fPS8EzhR92Dpr6h3w?usp=drive_link)
3. **Run all cells to see results**


## Future Improvements
- Try other models like **Gradient Boosting** or **XGBoost** for better accuracy.
- Hyperparameter tuning for Random Forest.
- Implement feature engineering for better insights.

## Repository
All the code and analysis are available in this GitHub repository: [GitHub Link](https://github.com/adibpriatama86/Car_Price_Prediction)

---
**Feel free to contribute or provide feedback! 🚀**


**Author: Ilham Adib Priatama**

**Contact:** [LinkedIn](http://linkedin.com/in/ilhamadibpriatama)

---

**Attachments:**


![heatmap korelasi](https://github.com/user-attachments/assets/1bedd38f-66d0-4414-9596-217a97a5f3ed)
![actual vs predicted](https://github.com/user-attachments/assets/e7997125-15cd-432a-8dcd-91e06acc7a4b)
