Titanic Dataset Analysis
Project Overview

This project explores the Titanic dataset from Kaggle using Python and popular data analysis libraries like pandas, numpy, matplotlib, and seaborn. The dataset contains information about passengers, including whether they survived, their age, gender, class, fare, and port of embarkation.

The goal of this project is to clean the data, explore it (EDA), and preprocess features to understand patterns and relationships that affect survival.

Data Cleaning

In this step, we handled missing or incomplete data:

Age: Filled missing values with the median age.

Embarked: Filled missing values with the most common port of embarkation (mode).

Exploratory Data Analysis (EDA)
Overview

Viewed summary statistics using df.describe().

Checked the first few rows of the dataset using df.head().

Checked data types and missing values using df.info().

Data Visualization

We explored patterns in the dataset using different plots:

Survival by Gender: Count plot to see how males and females survived.

Survival by Passenger Class: Count plot to see survival differences across classes.

Survival by Age & Fare: Histograms to understand age and fare distribution among survivors and non-survivors.

Correlation Heatmap: Visualized how numerical features relate to each other and to survival.

Data Preprocessing

One-hot Encoding: Converted the categorical column Embarked into numerical columns so it can be used in analysis.

Key Insights

Females had a higher survival rate than males.

First-class passengers were more likely to survive.

Children and those who paid higher fares had better survival chances.

Features like Pclass and Fare showed the strongest correlation with survival.

Conclusion

This analysis provides a clear understanding of the Titanic dataset, showing which factors influenced survival the most. These insights can be used for further analysis or predictive modeling to estimate passenger survival.
