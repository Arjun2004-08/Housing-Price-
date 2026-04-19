# 🏡 California Housing EDA & Data Visualization

## 📌 Overview

This project focuses on **Exploratory Data Analysis (EDA)** and **data visualization** of the California Housing dataset.
The goal is to understand data patterns, relationships, and key factors affecting house prices.

---

## 🎯 Objectives

* Understand distribution of features
* Detect outliers and anomalies
* Analyze relationships between variables
* Identify important features affecting house prices
* Prepare data for machine learning

---

## 📂 Dataset Features

* Longitude
* Latitude
* Housing Median Age
* Total Rooms
* Total Bedrooms
* Population
* Households
* Median Income
* Median House Value (Target)
* Ocean Proximity (Categorical)

---

## 🔍 EDA Steps Performed

### 1. Data Understanding

* Checked dataset structure using `.info()`
* Summary statistics using `.describe()`
* Identified missing values

---

### 2. Univariate Analysis

* Distribution plots (Histograms + KDE)
* Observed skewness in features like:

  * Population
  * Total Rooms
  * Median Income

---

### 3. Outlier Detection

* Used boxplots
* Found outliers in:

  * Population
  * Total Rooms
  * Median Income

---

### 4. Bivariate Analysis

* Scatter plots for feature relationships
* Key observation:

  * **Median Income strongly correlates with House Value**

---

### 5. Correlation Analysis

* Heatmap visualization
* Identified important features:

  * Median Income (strong positive correlation)
  * Location features (Latitude, Longitude)

---

### 6. Geographical Analysis

* Scatter plot of Latitude vs Longitude
* Color-coded by house value
* Revealed location-based price patterns

---

### 7. Categorical Analysis

* Count plots for Ocean Proximity
* Boxplots to compare house values across categories
* Observation:

  * Houses near ocean tend to have higher prices

---

### 8. Feature Engineering

Created new features:

* Rooms per Household
* Bedrooms per Room
* Population per Household

These improved relationships with target variable.

---

## 📊 Tools & Libraries Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

## 🚀 Key Insights

* Median Income is the **strongest predictor** of house value
* Location plays a **major role in pricing**
* Data contains **outliers and skewed distributions**
* Feature engineering significantly improves data quality

---

## 🔮 Future Work

* Apply machine learning models
* Feature selection & model tuning
* Build prediction system

---

## 📌 Conclusion

This EDA provides a strong foundation for building machine learning models by uncovering patterns, handling data issues, and identifying important features.

---
