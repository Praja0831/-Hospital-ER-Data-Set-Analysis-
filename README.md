🏥 Hospital ER Data Analysis Dashboard

This project analyzes hospital emergency room (ER) data using Power BI and Python. Dataset having more than 9.2k entry.
The dashboard provides actionable insights into patient admissions, demographics, and trends.

🔍 Key Insights: Monthly admission trends 📅
Age group distribution 👶👩‍🦳
Department-wise admissions 🏥
Gender and racial demographics 👨👩
Daily & monthly admission patterns

Power BI Analysis
1)I have find above mentioned KPI from Hospital ER Dataset.

2)Firstly i have check that data is clean and preprocess for visualization or Not.

3)Create some Measures For visualization.

4)Create the columns Day, Month and Year from Patient Admission Date Column.

5)Use Day and Month Column for Daily and Monthly Trend Analysis.

6)By Using the Columns Race and Gender visualize the racial demographics by gender.

7)Department wise Patient Admission

Python EDA Operations (Hospital_ER_EDA.ipynb)
📊 Operations Performed:

Data Loading & Overview - Load dataset, check shape, info, and statistical summary

Missing Value Analysis - Identify and quantify missing values in each column

Data Preprocessing - Convert date column, extract Year, Month, Day, Hour, and Day of Week

Univariate Analysis:

Gender distribution (bar & pie charts)
Age distribution (histogram & box plot)
Race distribution
Department Referral distribution
Wait time distribution
Satisfaction Score distribution
Admission Flag distribution
Temporal Analysis:

ER visits by Hour of Day
ER visits by Day of Week
ER visits by Month
Bivariate Analysis:

Wait time by Gender
Wait time by Department
Satisfaction Score by Department
Age Group analysis
Wait time by Age Group
Wait time vs Satisfaction Score correlation
Correlation Heatmap - Visualize correlations between numeric variables

Key Insights Summary - Generate summary statistics and findings

📦 Required Libraries: pandas, numpy, matplotlib, seaborn
