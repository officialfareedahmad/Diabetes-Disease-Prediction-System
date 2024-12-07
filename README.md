# Diabetes Disease Prediction System using Machine Learning

## Overview
This project is designed to predict the presence of diabetes in patients based on their medical records. It uses machine learning algorithms to analyze features such as glucose levels, insulin, BMI, and age, delivering predictions with high accuracy.

## Features
- **Python-based Implementation:** Fully developed using Python for data processing, visualization, and modeling.
- **Data Preprocessing:** Includes handling missing values, outlier detection, and scaling using standardization techniques.
- **Exploratory Data Analysis (EDA):** Comprehensive visualizations like distributions, correlations, and count plots for better insights.
- **Machine Learning Models:** Multiple algorithms implemented, such as:
  - Logistic Regression
  - Support Vector Machines (SVM)
  - Random Forest
  - Gradient Boosting
- **Model Evaluation:** Performance analyzed using metrics like:
  - Accuracy
  - Confusion Matrix
  - ROC-AUC Curve
  - Classification Report
- **Prediction System:** Real-time predictions based on user inputs, integrated with an interactive UI (Streamlit or Flask).

## Tools and Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Missingno
- Scikit-learn
- Statsmodels

## How It Works
1. **Dataset Preparation:**
   - Imported dataset and cleaned missing/incorrect data using libraries like Pandas and Missingno.
   - Scaled numerical features to standardize the dataset.
   
2. **EDA (Exploratory Data Analysis):**
   - Visualized relationships between features such as glucose levels and diabetes outcomes.
   - Used heatmaps, pair plots, and pie charts for better understanding.

3. **Model Training:**
   - Split the data into training and testing sets (e.g., 80-20 split).
   - Trained multiple models, tuned hyperparameters, and selected the best-performing model.

4. **Model Evaluation:**
   - Evaluated predictions on training and test data using confusion matrix and ROC-AUC scores.

5. **Prediction System:**
   - Built an interactive interface where users can input patient data and receive real-time predictions.
