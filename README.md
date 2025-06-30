# Task5
Task 5: Exploratory Data Analysis (EDA) – Titanic Dataset
 Objective
The goal of this task is to extract insights from the Titanic dataset using visual and statistical exploration methods. This helps uncover trends, patterns, and anomalies that inform better decision-making and understanding of the data.

🛠️ Tools Used
Python 3
Pandas – data manipulation
Matplotlib & Seaborn – data visualization
Jupyter Notebook – for code execution and reporting

 Key Steps Performed
1. Data Loading and Overview
Checked structure, types, and summary statistics using .info() and .describe()
Identified missing values in Age, Cabin, and Embarked
2. Univariate Analysis
Plotted histograms for Age and Fare
Used countplots for Survived, Sex, and Pclass
3. Bivariate Analysis
Explored relationships using:
Boxplots (Age, Fare vs Survived)
Correlation heatmap
Pairplot for numeric features
4. Observations Noted
Women and children had higher survival rates
1st class passengers had better chances of survival
Older passengers and those who paid lower fares had lower survival rates

Summary of Findings
Survival Rate: Only ~38% of passengers survived

Gender Impact: Females were more likely to survive

Class Factor: Higher class = higher chance of survival

Fare Trends: Passengers who paid more were more likely to survive

Missing Data: Notable in Age, Cabin, and Embarked
