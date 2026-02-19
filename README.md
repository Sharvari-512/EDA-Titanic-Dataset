Project Overview
This project focuses on performing Exploratory Data Analysis (EDA) on the Titanic dataset obtained from Kaggle.
The objective of this task is to extract meaningful insights, identify patterns, and understand the factors influencing passenger survival using statistical techniques and data visualization.

Objective
- To understand the dataset structure and features
- To identify and handle missing values
- To perform univariate, bivariate, and multivariate analysis
- To analyze survival patterns
- To determine the most influential features affecting survival

Dataset Information
- Dataset Name: Titanic Dataset
- Total Records: 891
- Total Features: 12
- Target Variable: Survived
  - 0 → Did Not Survive
  - 1 → Survived

Tools & Libraries Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

Initial Data Exploration
The following functions were used to understand the dataset:
- .info() → Checked data types and missing values
- .describe() → Generated statistical summary
- .value_counts() → Analyzed categorical distributions
Key Observations:
- Missing values found in Age and Cabin
- Average passenger age ≈ 29 years
- Fare distribution is highly skewed
- Around 38% passengers survived
- Majority passengers were male and traveled in 3rd class

Analysis Performed
1. Univariate Analysis
- Survival distribution
- Gender distribution
- Passenger class distribution
- Age distribution

4️. Bivariate Analysis
- Survival vs Gender
- Survival vs Passenger Class
- Survival vs Age

5️. Multivariate Analysis
- Correlation heatmap
- Survival analysis across Gender & Class

Key Insights
- Gender is the strongest predictor of survival.
- First-class passengers had significantly higher survival rates.
- Higher fare is positively correlated with survival.
- Age has moderate influence.
- Small family sizes showed better survival probability.
- Dataset shows class imbalance (more non-survivors than survivors).

Conclusion
The exploratory data analysis revealed that survival during the Titanic disaster was strongly influenced by gender, passenger class, and fare. Socioeconomic factors played a major role in determining survival probability.
This analysis establishes a solid foundation for future predictive modeling and machine learning applications.
