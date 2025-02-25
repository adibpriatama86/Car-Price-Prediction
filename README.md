# Car Price Prediction using Machine Learning

## Overview
This project aims to predict car prices using various machine learning models, including **Linear Regression, Random Forest, and XGBoost**. After experimenting with multiple models, **XGBoost with hyperparameter tuning achieved the best performance**.

## Dataset
The dataset used in this project is sourced from [Kaggle](https://www.kaggle.com/datasets/asinow/car-price-dataset) and includes the following columns:
- **Brand**
- **Model**
- **Year**
- **Engine_Size**
- **Fuel_Type**
- **Transmission**
- **Mileage**
- **Doors**
- **Owner_Count**
- **Price** (Target Variable)

## Steps
1. **Data Preparation**: Handling missing values, feature encoding, and scaling.
2. **Exploratory Data Analysis (EDA)**: Understanding distributions, correlations, and feature importance.
3. **Model Training & Evaluation**:
   - **Linear Regression** (Baseline model)
   - **Random Forest** (Tree-based model)
   - **XGBoost** (Final best-performing model)
4. **Hyperparameter Tuning** (for XGBoost) using `RandomizedSearchCV`.

## Results
### **1️⃣ Baseline Models**
- **Linear Regression**
  - R² Score: **0.9995**
  - MSE: **4213.92**
- **Random Forest**
  - R² Score: **0.9708**
  - MSE: **268439.56** (after tuning)

### **2️⃣ Best Performing Model: XGBoost**
- **Final XGBoost Results (After Hyperparameter Tuning):**
  - **R² Score**: **0.9970**
  - **MSE**: **27948.18**
  - **Best Parameters**:  
    ```json
    {
      'subsample': 0.8,
      'n_estimators': 200,
      'max_depth': 5,
      'learning_rate': 0.1,
      'colsample_bytree': 1.0
    }
    ```

## Visualizations
![scatter plot](https://github.com/user-attachments/assets/c61ce5c4-98fc-4db6-93af-f04f5f09955d)
*(Example of a scatter plot comparing actual vs predicted prices)*

## Requirements
- Python 3.x
- Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, XGBoost

## How to Run
1. **Clone this repository**:
   ```bash
   git clone https://github.com/adibpriatama86/Car-Price-Prediction.git
   ```
2. **Open the Jupyter Notebook or Google Colab**:
   - Jupyter Notebook: `Car_Price_Prediction.ipynb`
   - Google Colab: [Colab Link](https://colab.research.google.com/drive/1HPJ97Q962sZvolwofGas-zeHwHBUBi37?usp=sharing)
3. **Run all cells to see results**

## Key Takeaways
- **XGBoost significantly outperformed other models** after tuning.
- **Feature selection & proper hyperparameter tuning** greatly improved accuracy.
- **Linear Regression, while highly accurate, showed signs of overfitting**.

---
🚀 **Future Work:**
- Experiment with **Deep Learning models** (e.g., Neural Networks)
- Add more **feature engineering techniques** for better accuracy
- Deploy the model as a **web app** for real-world predictions!

👨‍💻 **Author:** Ilham Adib Priatama

**Contact:** [LinkedIn](http://linkedin.com/in/ilhamadibpriatama)
