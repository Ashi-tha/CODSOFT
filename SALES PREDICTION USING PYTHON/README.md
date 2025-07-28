📊 Sales Prediction using Advertising Spend

📌 Overview
This project focuses on building a Sales Prediction model using historical advertising data. It aims to understand how TV, Radio, and Newspaper advertisement expenditures influence product sales, helping businesses make smarter marketing decisions.

This project was developed as part of my Data Science Internship at CODSOFT.

🎯 Objective
Predict product sales based on different advertisement channel spends using regression models and evaluate their performance.

🛠️ Tools & Technologies
Language: Python

Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, SHAP

Models: Linear Regression, Random Forest Regressor

Environment: Google Colab / Jupyter Notebook

Optional: Power BI (for dashboarding with exported results)

📁 Dataset
The dataset advertising.csv contains:

TV: Advertising budget spent on TV

Radio: Advertising budget spent on Radio

Newspaper: Advertising budget spent on Newspaper

Sales: Product sales outcome (target variable)

🔍 Exploratory Data Analysis (EDA)
Pair plots between features and target

Correlation heatmap to study multicollinearity

Visual inspection of linearity and feature impact

🔧 Model Building
Two models were developed and compared:

Model	Evaluation Metrics Used
Linear Regression	R² Score, MSE
Random Forest	R² Score, MSE

🧠 Explainable AI with SHAP
To understand which features influenced the prediction most, SHAP (SHapley Additive exPlanations) was used. This helps bring transparency to model behavior.

✨ Key Features
✅ Model Training & Evaluation (Linear and Ensemble)

✅ Real-time Interactive Input Prediction

✅ SHAP-based Feature Importance Visualizations

✅ Exporting predictions for BI dashboards (e.g., Power BI)

✅ Clean, modular, beginner-friendly code

🚀 Try It Yourself (Command Line Version)
python
Copy
Edit
# Example: Input Advertising Spend
TV = 150
Radio = 35
Newspaper = 45

# Predict sales using trained model
Or use the Streamlit version for a web interface (optional).

📤 Output File
sales_predictions.csv – Contains actual vs predicted values on test set

Ideal for visualization in tools like Power BI or Tableau

📈 Sample Results
TV has the highest influence on sales

Newspaper had minimal impact

Random Forest slightly outperformed Linear Regression

SHAP plots clearly visualized feature contributions

🔮 Future Improvements
Add digital ad platforms (e.g., social media spend)

Incorporate time-based features (seasonality, campaigns)

Deploy as a live Streamlit web app

