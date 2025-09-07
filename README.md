🏥 Healthcare Insurance Cost Analysis

This project analyzes the Healthcare Insurance dataset to explore factors that influence medical charges. The goal is to identify key drivers of insurance costs, detect outliers, and provide actionable insights for individuals, insurance companies, and policymakers.

📊 Dataset Information

Rows (records): 1338

Columns (features): 7

Features:

age → Age of the insured person

sex → Gender (male/female)

bmi → Body Mass Index (health indicator)

children → Number of dependents covered by insurance

smoker → Smoking status (yes/no)

region → Residential region (northeast, northwest, southeast, southwest)

charges → Medical insurance cost billed

🛠️ Tech Stack

Language: Python

Libraries: Pandas, NumPy, Matplotlib, Seaborn

Data Source: insurance.xlsx

📂 Project Workflow

Data Cleaning & Preprocessing → Handling missing values, filtering out outliers (charges ≥ 50,000).

Exploratory Data Analysis (EDA) → Studying relationships between features and charges.

Data Visualization → Scatter plots, box plots, bar plots, correlation heatmaps.

Insights & Recommendations → Deriving meaningful conclusions for individuals, insurers, and policymakers.

🔎 Key Insights

Age → Charges rise steadily with age, especially after 50.

BMI → Higher BMI (obesity >30) significantly increases medical costs.

Smoker Status → Strongest predictor of charges; smokers pay 3x+ more.

Sex & Children → Minimal influence on medical expenses.

💡 Recommendations

For Individuals → Quit smoking, maintain a healthy BMI, and plan early for rising age-related costs.

For Insurance Companies → Use smoker status and BMI as key factors for premium calculation, introduce wellness programs.

For Policymakers → Promote anti-smoking and obesity-prevention programs, encourage insurers to reward preventive care.
