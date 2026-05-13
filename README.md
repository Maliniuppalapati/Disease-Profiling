🏥 HealthPredict AI: Disease Symptom & Patient Profile Analysis
📌 Project Overview

HealthPredict AI is an end-to-end data science project that models the relationship between clinical symptoms and diagnostic outcomes. Using patient demographics and symptom data, the system predicts disease likelihood and demonstrates how machine learning can assist early-stage healthcare decision-making.

This project showcases the complete data science lifecycle—from data cleaning and exploratory analysis to feature engineering, model building, and evaluation.

🚀 Key Features
🔄 Automated Data Pipeline
Handles duplicate removal and feature classification (categorical vs. numerical)
📊 Exploratory Data Analysis (EDA)
Disease distribution across age groups and gender
Symptom correlation analysis with outcomes
🧠 Feature Engineering
One-Hot Encoding for categorical variables
Label Encoding for target variables
Expansion to 126 engineered features
🤖 Predictive Modeling
Comparative analysis of multiple classification models
Focus on healthcare-relevant metrics (recall & precision)
🛠️ Technical Stack
Language: Python 3.x
Data Processing: Pandas, NumPy
Visualization: Matplotlib, Seaborn, Plotly Express
Machine Learning: Scikit-Learn
Environment: Jupyter Notebook / Google Colab
📊 Dataset Summary
Initial Size: 349 records × 10 columns
After Cleaning: 300 unique patient records
Duplicates Removed: 49

Features Include:

Symptoms: Fever, Cough, Fatigue, Difficulty Breathing
Demographics: Age (19–90), Gender
Clinical Metrics: Blood Pressure, Cholesterol
Target Variable: Disease Outcome (Positive / Negative)
📈 Model Performance
Model	Accuracy	Precision	Recall
Random Forest	78.3%	80%	78%
Decision Tree	70.0%	70%	70%
Logistic Regression	68.3%	68%	68%

✅ Best Model: Random Forest Classifier

Achieved ~90% recall for positive cases
Crucial for reducing false negatives in healthcare predictions
📂 Project Structure
├── disease_symptom.csv       # Clinical dataset  
├── Disease_Symptoms_ML_Modelling.ipynb   # Data cleaning, EDA, ML models  
├── README.md                 # Documentation  
└── requirements.txt          # Dependencies  
💻 How to Run
# Clone the repository
git clone https://github.com/your-username/HealthPredict-AI.git

# Install dependencies
pip install pandas numpy seaborn matplotlib plotly scikit-learn

Open Disease_Symptoms_ML_Modelling.ipynb in Jupyter Notebook or Google Colab and run all cells.

📌 Key Insights
Total unique patients analyzed: 300
Unique diseases identified: 116
Most represented age group: ~45 years
Best-performing algorithm: Random Forest (Scikit-Learn)
