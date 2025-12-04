# mental-health-prediction


🧠 Mental Health Prediction using Machine Learning
📋 Overview

This project analyzes the Mental Health in Tech Industry dataset to understand key factors influencing whether individuals seek mental health treatment. Using data science and machine learning techniques, the project identifies workplace, demographic, and behavioral attributes associated with mental health awareness and support.

🎯 Objectives

Predict the likelihood of a person seeking mental health treatment.

Identify the top influential factors affecting mental wellness in tech workplaces.

Explore correlations between remote work, company size, and mental health.

Provide actionable insights to promote healthier and more supportive work environments.

📊 Dataset Information

Dataset: Mental Health in Tech Survey (2014–2016)

Records: 1,259

Features: 27

Target Variable: treatment (Whether the respondent sought mental health treatment)

Column Name	Description	Type
Age	Age of respondent	Numeric
Gender	Gender identity	Categorical
Country	Country of residence	Categorical
self_employed	Employment type	Binary
family_history	Family history of mental illness	Binary
treatment	Sought mental health treatment (Target)	Binary
work_interfere	Work interference due to mental issues	Ordinal
no_employees	Company size	Categorical
remote_work	Works remotely	Binary
benefits	Availability of mental health benefits	Binary
🔄 Data Science Workflow

Problem Definition – Understanding the goal and success metrics.

Data Cleaning – Handling missing values, encoding categorical variables, and correcting inconsistencies.

Exploratory Data Analysis (EDA) – Identifying correlations, visualizing trends, and detecting feature significance.

Feature Engineering – Label encoding and scaling relevant features.

Model Training & Evaluation – Comparing ML algorithms for performance.

Insights & Visualization – Communicating findings with graphs and metrics.

🧩 Machine Learning Models Used
Model	Accuracy	F1-Score
Logistic Regression	82%	0.76
Decision Tree	80%	0.73
Random Forest	85%	0.78
SVM (Support Vector Machine)	83%	0.75

✅ Best Model: Random Forest Classifier
✅ Top Influential Factors:

Work interference level

Family history

Mental health benefits availability

Company size

Remote work status

📈 Visual Insights

Gender-based analysis: Female respondents reported higher interference from mental health issues.

Company size correlation: Smaller companies showed fewer mental health resources.

Remote work: Those with remote work options reported better mental health balance.

🛠️ Technologies Used

Language: Python

Libraries: NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn

Environment: Jupyter Notebook

▶️ How to Run the Project

Clone the repository:

git clone https://github.com/akhilpinninti/mental-health-prediction.git
cd mental-health-prediction


Install dependencies:

pip install -r requirements.txt


Open the notebook:

jupyter notebook mental_health_analysis.ipynb


Run all cells to reproduce the analysis and visualizations.

📚 Results Summary

Achieved 85% accuracy and F1-score of 0.78 using Random Forest.

Identified key predictors of mental health treatment seeking.

Highlighted trends to encourage mental health awareness in workplaces.

💡 Future Improvements

Incorporate deep learning models for enhanced feature interactions.

Deploy a Flask-based web dashboard for real-time predictions.

Use newer datasets (post-2020) for updated insights.
