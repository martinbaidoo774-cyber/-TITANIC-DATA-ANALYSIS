# README – Titanic Data Analysis

## Project Overview
This project analyzes the **Titanic passenger dataset** to identify factors that influenced survival during the Titanic disaster and to build a machine learning model capable of predicting passenger survival. The work demonstrates a complete data science workflow, including data cleaning, exploratory analysis, visualization, statistical analysis, and predictive modeling. 
## Dataset
The analysis used the Titanic dataset from Kaggle:

- **train.csv**: 891 passenger records with survival information.
- **test.csv**: 418 passenger records without survival outcomes. 

Key variables included passenger class, age, sex, fare, family relationships, embarkation point, and cabin information. Several columns contained missing values that were addressed during preprocessing.
## Methodology
The project followed these main steps:

1. **Data Acquisition**
   - Loaded and inspected the dataset.
   - Examined structure, columns, and data types.

2. **Data Cleaning**
   - Handled missing values in Age and Embarked.
   - Replaced the Cabin column with a binary **HasCabin** indicator.
   - Checked for duplicate records.

3. **Exploratory Data Analysis (EDA)**
   - Created visualizations including histograms, boxplots, scatter plots, heatmaps, and pairplots.
   - Explored patterns and relationships among variables.

4. **Statistical Analysis**
   - Generated descriptive statistics.
   - Conducted frequency and correlation analysis.

5. **Machine Learning**
   - Built a **Logistic Regression** model.
   - Encoded categorical variables.
   - Split data into training (80%) and testing (20%) sets.
   - Evaluated performance using accuracy, confusion matrix, and classification report. 

## Key Findings
- Most passengers were between **20 and 40 years old**.
- **Third-class passengers** constituted the largest group onboard.
- Higher ticket fares were associated with higher survival rates.
- Passenger class had a strong influence on survival.
- Age alone had a relatively weak relationship with survival.
- Gender significantly affected survival, with females having higher survival rates. 
## Conclusion
The study successfully demonstrated how data science techniques can be applied to a real-world dataset. The analysis showed that **passenger class, fare, and gender** were among the strongest factors influencing survival. The Logistic Regression model provided strong baseline performance, while future improvements could include feature engineering, cross-validation, and advanced algorithms such as Random Forest or XGBoost.

**Author:** Martin Baidoo  
**Course:** Data Science with Python  
**Date:**  July 2026 
