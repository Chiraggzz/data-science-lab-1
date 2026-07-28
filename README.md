# BCSE0593: Data Science and Visualization Lab - Experiment 01

## 📝 Experiment Description
This repository contains the work for Experiment 01: Exploring Kaggle & GitHub. The objective was to set up platform accounts, download an open-source dataset from Kaggle, perform preliminary Exploratory Data Analysis (EDA) using Python (Pandas), and upload the artifacts to this GitHub repository for version control.

## 📊 Dataset Information
- **Dataset Name:** Titanic - Machine Learning from Disaster
- **Source URL:** https://www.kaggle.com/datasets/shuofxz/titanic-machine-learning-from-disaster/data

## 🔍 EDA Key Observations
Preliminary analysis was performed using `analysis.ipynb`. Key findings include:
- **Structure:** The dataset contains 891 rows (passengers) and 12 columns (features).
- **Data Types:** A mix of numeric (`int64`, `float64`) and categorical (`object`) features.
- **Missing Values:** 
  - `Cabin`: 687 missing values (mostly empty).
  - `Age`: 177 missing values.
  - `Embarked`: 2 missing values.
- **Summary Statistics:** 
  - **Survival Rate:** Approximately 38.4% of passengers in this dataset survived (`Survived` mean = 0.384).
  - **Age:** The average age is ~29.7 years, ranging from 0.42 to 80 years.
  - **Fare:** The average fare is ~$32.20, with a maximum fare of $512.33.

## 📂 Repository Contents
- `dataset.csv` : The raw dataset downloaded from Kaggle.
- `analysis.ipynb` : Jupyter Notebook containing the Python EDA code and outputs.
- `README.md` : This documentation file.

---
*Student Name:* [Chirag Chaudhary]  
