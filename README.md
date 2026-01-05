Titanic Dataset Analysis
Project Overview

This project involves exploring the Titanic dataset from Kaggle using Python and popular data analysis libraries such as pandas, numpy, matplotlib, and seaborn. The dataset contains information about passengers on board the Titanic, including whether they survived, their age, gender, class, fare, and port of embarkation.

The goal of this project is to perform data cleaning, exploratory data analysis (EDA), and feature preprocessing to understand relationships between variables, identify patterns, and extract insights related to survival.


Data Cleaning
In the data cleaning phase, we performed the following operations:

Handling missing values:
Age: Missing values were replaced with the median age.
Embarked: Missing values were replaced with the mode (most common value).
Exploratory Data Analysis (EDA)
Summary Statistics
We displayed the summary statistics of the dataset using df.describe().

Data Overview
We displayed the first few rows of the dataset to get an overview of its structure using df.head().

Data Information
We printed information about the dataset, including data types and non-null counts using print(df.info()).

Data Visualization
We used data visualization techniques to explore relationships and patterns in the dataset:

Survival by Sex: We created a count plot to visualize survival by gender.
Survival by Passenger Class: We created a count plot to visualize survival by passenger class.
Survival by Age: We used a histogram to visualize the age distribution of survivors and non-survivors.
Survival by Fare: We used a histogram to visualize the fare distribution of survivors and non-survivors.
Correlation Heatmap: We generated a heatmap to visualize the correlation between various numerical features and survival.
Age and Fare Distribution
We explored the distribution of passengers' ages and fares using histograms.

Data Preprocessing
One-hot Encoding: We performed one-hot encoding on the 'Embarked' column to convert categorical data into numerical format.

Conclusion
This analysis provides valuable insights into the Titanic dataset, including the distribution of passengers, relationships between variables, and patterns related to survival. Notable findings include the higher survival rate among females, first-class passengers, children, and passengers who paid higher fares.
