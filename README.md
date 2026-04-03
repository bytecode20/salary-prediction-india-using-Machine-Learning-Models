# salary-prediction-india-using-Machine-Learning-Models

💼 Salary Prediction in India using Machine Learning

📌 Project Overview

This project aims to predict salaries in India based on years of experience using various regression algorithms. It compares multiple machine learning models to determine which provides the most accurate predictions.

The project includes data analysis (EDA), model training, and performance comparison.

🎯 Objectives
Analyze the relationship between experience and salary
Apply multiple regression models
Compare model performance using evaluation metrics
Identify the best model for prediction

📊 Dataset
Feature: YearsExperience
Target: Salary
Dataset size: ~6500+ entries
Cleaned by removing missing values

🔍 Exploratory Data Analysis (EDA)

The dataset was analyzed using:

Distribution plots (Salary & Experience)
Scatter plot (Salary vs Experience)
Correlation heatmap
Boxplot for outlier detection

👉 Key Insight:

Salary increases linearly with experience, making it suitable for regression models.

🤖 Models Used
Simple Linear Regression
Multiple Linear Regression
Polynomial Regression
Support Vector Regression (SVR)
Decision Tree Regression
Random Forest Regression

📈 Model Evaluation

Models were evaluated using:

R² Score (Accuracy)
Mean Squared Error (MSE)

🏆 Best Performing Model:
👉 Random Forest Regression (based on highest R² score)

📊 Results Visualization

The project includes:

Graphical comparison of all models
Salary vs Experience plots
Model performance bar charts
🛠️ Tech Stack
Python 🐍
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Jupyter Notebook

📁 Project Structure
salary-prediction-india/
│
├── data/
│   └── salary_data.csv
│
├── notebooks/
│   └── salary_prediction_master_notebook.ipynb
│
├── results/
│   └── model_comparison.csv
│
├── README.md
└── requirements.txt

🚀 How to Run
Clone the repository:
git clone https://github.com/your-username/salary-prediction-india.git

Install dependencies:
pip install -r requirements.txt

Run the notebook:
jupyter notebook

📌 Key Learnings
Importance of data preprocessing
Comparison of regression algorithms
Handling missing values
Visualizing model performance

👨‍💻 Author
Arjun Johari
