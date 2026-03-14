This project analyzes a heart disease dataset to identify patterns and risk factors associated with heart disease. Using Python data analysis libraries, the project performs data cleaning, exploratory data analysis (EDA), and visualization to understand how different health parameters influence heart disease.

 Objective

The objective of this project is to explore patient health data and analyze factors that contribute to heart disease using data visualization and statistical insights.

Dataset

The dataset used is heart.csv, which contains medical attributes related to heart health.

Features include:

Age

Sex

ChestPainType

RestingBP (Resting Blood Pressure)

Cholesterol

Fasting Blood Sugar

MaxHR (Maximum Heart Rate)

ExerciseAngina

Oldpeak

ST_Slope

HeartDisease (Target Variable)

Technologies Used

Python

Jupyter Notebook

Pandas

NumPy

Matplotlib

Seaborn

 Project Workflow
1️ Data Loading

The dataset is imported using Pandas.

2️ Data Cleaning

Checked for missing values

Replaced invalid values (0) in Cholesterol and RestingBP with mean values.

3️ Exploratory Data Analysis (EDA)

Performed analysis using:

Histograms

Count plots

Box plots

Violin plots

4️ Data Visualization

Used Seaborn and Matplotlib to visualize relationships between features and heart disease.

5️ Correlation Analysis

Heatmap used to understand correlations between numerical features.

 Key Insights

Age and cholesterol levels influence heart disease risk.

Certain chest pain types show higher association with heart disease.

Heart rate and blood pressure also show notable patterns.
