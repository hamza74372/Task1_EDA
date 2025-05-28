# Task 1 – Exploratory Data Analysis (EDA) and Visualization

## 📌 Project Overview
This task involves performing Exploratory Data Analysis (EDA) on the Titanic dataset. The goal is to clean the data, analyze feature distributions, and derive meaningful insights through visualizations.

## 🔧 Steps Performed

### 1. Loading the Dataset
- Loaded the Titanic dataset using pandas and explored its structure.

### 2. Data Cleaning
- Handled missing values in columns like `Age`, `Embarked`, and `Cabin`.
- Removed duplicate entries.
- Detected and treated outliers using boxplots and domain understanding.

### 3. Data Visualization
- Plotted bar charts for categorical features (e.g., `Sex`, `Pclass`, `Embarked`).
- Plotted histograms for numerical features (e.g., `Age`, `Fare`).
- Created a correlation heatmap to understand feature relationships.

### 4. Insights & Observations
- Higher survival rates were observed in females and passengers in first class.
- Missing values in `Age` were imputed with median age.
- `Fare` showed a right-skewed distribution with some high-value outliers.
- Correlation heatmap revealed moderate correlations between `Fare`, `Pclass`, and `Survived`.

## 📁 Files Included
- `Task1_EDA.ipynb`: Colab notebook with full code and visualizations.
- Sample outputs and plots inline within the notebook.

## 🚀 How to Run
1. Clone the repository or open the notebook in Google Colab.
2. Run all cells step-by-step to reproduce the analysis and visualizations.

## ✅ Outcome
- A clean and well-explored dataset with visual insights ready for further modeling.
