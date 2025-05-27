# PRODIGY_TASK2
# 🧹 Task 2: Data Cleaning & Exploratory Data Analysis (EDA)

This repository contains the second task of my Data Science Internship at **Prodigy InfoTech**, where I performed detailed **data cleaning** and **exploratory data analysis** on a real-world employee dataset.

## 📌 Objective

The goal of this task is to:
- Clean and preprocess the dataset by handling missing values, incorrect data, duplicates, and outliers.
- Perform exploratory data analysis to understand the structure, patterns, and relationships within the data.
- Visualize the findings using plots and statistical summaries.

## 🧼 Data Cleaning Steps

- Replaced incorrect values (e.g., `0` in `Age`) with `NaN`.
- Handled missing values:
  - Used **median** for numeric columns like `Age` and `Salary`.
  - Used **mode** for categorical columns like `Company`, `Place`, and `Gender`.
- Removed duplicate records.
- Identified outliers using the **IQR (Interquartile Range)** method and visualized them using boxplots.

## 🔍 Exploratory Data Analysis (EDA)

Performed a comprehensive analysis using:
- **Descriptive statistics** to understand central tendency and spread.
- **Distribution plots** (histograms & KDE) for numeric variables like `Age` and `Salary`.
- **Count plots** for categorical variables like `Company`, `Place`, and `Gender`.
- **Scatter plots** to examine relationships (e.g., `Age` vs `Salary`).
- **Boxplots** to visualize salary distribution across companies.
- **Heatmaps** for correlation analysis between numerical features.

## 📊 Visualizations Included

- Boxplots to detect outliers
- Histograms and KDE plots for distributions
- Countplots for frequency of categorical values
- Correlation matrix heatmap
- Scatter plot: Age vs Salary
- Company-wise salary distribution

## 🛠️ Tools Used

- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib

## 📁 Dataset Description

The dataset contains employee records with the following fields:
- `Company`: Name of the employer (e.g., TCS, Infosys, CTS)
- `Age`: Employee age (contains missing or incorrect values)
- `Salary`: Monthly salary
- `Place`: City of employment
- `Country`: Country (all India)
- `Gender`: 0 for Male, 1 for Female

## 🔗 Outcome

This task helped build a strong foundation in:
- Data preprocessing
- Feature inspection
- Pattern recognition through visualization
- Data-driven decision-making


