# Weather Prediction Using Machine Learning

This project implements a weather prediction model using machine learning in Python. It covers the full pipeline from **data collection**, **preprocessing**, and **exploratory data analysis (EDA)** to model building and evaluation.

---

## Project Overview

The goal is to predict whether it will rain the next day (`RainTomorrow`) based on weather data features such as temperature, humidity, wind speed, and pressure.

---

## Contents

- `Wether.ipynb` — Complete Python script including:
  - Loading and inspecting the dataset
  - Handling missing values and duplicates
  - Feature selection and encoding
  - Data integrity checks and summary statistics
  - Exploratory Data Analysis (EDA) with visualizations
  - Outlier detection and handling
  - Correlation analysis

---

## Dataset

The dataset should be named `weather.csv` and placed in the same folder as the script. It contains weather-related measurements and a target variable indicating rainfall the next day.

---

## Key Steps

### 1. Data Collection & Preprocessing
- Loading the dataset from CSV
- Cleaning missing data (imputation and dropping)
- Encoding categorical variables (e.g., RainToday, RainTomorrow)
- Ensuring data consistency and removing duplicates

### 2. Exploratory Data Analysis (EDA)
- Summary statistics and data types overview
- Visualizing distributions and relationships (heatmaps, pairplots)
- Detecting and handling outliers (e.g., capping rainfall values)

---

## Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

Install dependencies with:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
