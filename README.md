# Student Performance Prediction using ML Pipeline

This project demonstrates a clean, production-ready Machine Learning pipeline using Python and Scikit-learn to predict student exam scores based on study hours.

## 🚀 Features & Workflow
- **Data Preprocessing:** Handled missing values using `SimpleImputer` and scaled features using `StandardScaler`.
- **Feature Engineering:** Applied 'PolynomialFeatures' to capture non-linear relationships.
- **Model Training:** Trained a robust `LinearRegression` model wrapped inside a Scikit-learn `Pipeline`.
- **Evaluation:** Evaluated performance using **R² Score** and **Root Mean Squared Error (RMSE)**.
- **Prediction Function:** Includes a custom modular function to predict scores for new student inputs seamlessly.

## 🛠️ Tech Stack
- **Python**
- **Pandas & NumPy** (Data Manipulation)
- **Scikit-learn** (ML Pipelines & Modeling)
- **Matplotlib** (Data Visualization)

## 📊 Results
- **R² Score:** ~0.95 (High Accuracy)
- Visualizations include actual vs. predicted polynomial regression curves.
