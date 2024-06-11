# Task-02: Data Cleaning and Exploratory Data Analysis (EDA) on the Titanic Dataset
# Introduction
This project involves performing data cleaning and exploratory data analysis (EDA) on the Titanic dataset from Kaggle. The goal is to uncover relationships between variables and identify patterns and trends that can provide insights into the factors affecting survival rates on the Titanic.

# Dataset
Dataset Name: Titanic - Machine Learning from Disaster      
Source: https://www.kaggle.com/c/titanic/data

# Project Steps
The project began with data cleaning, where missing values in the Age column were imputed using the median age, missing Embarked values were filled with the most frequent port, and missing Cabin values were marked as 'Unknown'. Data types were converted appropriately, with Age transformed to numeric and Embarked to categorical. After ensuring there were no duplicate entries, outliers in the Fare and Age columns were identified and addressed.

Following data cleaning, exploratory data analysis (EDA) was conducted. Descriptive statistics were computed for both numerical and categorical features. Data visualization techniques were employed, starting with univariate analysis to visualize distributions of individual variables using histograms and bar charts. Bivariate analysis was then performed to explore relationships between pairs of variables through scatter plots and box plots. Multivariate analysis investigated interactions among multiple variables using pair plots and heatmaps. This analysis focused on identifying patterns and trends, such as examining survival rates based on gender, class, and age, analyzing the influence of fare and passenger class on survival, and exploring the impact of family size on survival rates.

# Key Findings
Survival Rates: Females, younger passengers, and those in higher classes had higher survival rates.
Fare Impact: Higher fares were associated with better chances of survival.
Family Size: Smaller family sizes correlated with higher survival probabilities.
Tools and Libraries
Programming Language: Python
Libraries: pandas, numpy, matplotlib, seaborn, scipy
