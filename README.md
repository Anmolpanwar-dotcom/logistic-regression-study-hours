# logistic-regression-study-hours
A Binary Classification model using Logistic Regression and Polynomial Features to predict student results (Pass/Fail) based on study hours, including accuracy analysis and visualization.
#  Student Result Prediction (Pass/Fail)

This project uses **Logistic Regression** to classify whether a student will pass or fail based on the number of study hours. It demonstrates how machine learning can find a "threshold" for success.

## 📊 Dataset Overview
The dataset contains:
- **Hours:** Number of hours spent studying (Independent Variable).
- **Result:** 0 for Fail, 1 for Pass (Dependent Variable).

## 🛠️ Tech Stack
- **Python**
- **Scikit-Learn** (Model training & metrics)
- **Pandas** (Data handling)
- **Matplotlib** (Data visualization)

## 🚀 Key Features
- **Polynomial Features:** Used degree 2 to capture non-linear relationships.
- **Model Evaluation:** Includes a **Confusion Matrix** and **Accuracy Score** to measure performance.
- **Data Splitting:** 50/50 Train-Test split for model validation.

## 📈 Results & Visualization
The project includes a bar chart showing the direct relationship between study hours and the outcome. Students studying for 5 hours or more consistently show a passing result.
