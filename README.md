# Lead Scoring Using Logistic Regression
This project aims to build a lead scoring system using Python and logistic regression. It involves data cleaning, exploratory data analysis, binary classification modeling, and a scoring algorithm to categorize leads based on their conversion probability.

##  Packages Used
pandas
numpy
matplotlib
seaborn
scikit-learn

##  Project Workflow
### 1. Data Loading & Initial Exploration
Loaded lead dataset (Leads.csv) using pandas.

Performed initial inspections including shape, data types, and missing value counts.

### 2. Data Cleaning & Transformation
Dropped columns with more than 50% missing values.

Filled remaining missing values using mode or median.

Encoded binary categorical columns (Do Not Email, Do Not Call).

Standardized text fields to eliminate inconsistent formatting (e.g., 'Google' vs 'google').

### 3. Exploratory Data Analysis (EDA)
Visualized target class distribution.

Created correlation heatmap of numeric variables.

Used bar plots, histograms, and box plots to explore feature relationships with conversion.

### 4. Logistic Regression Modeling
Selected numeric and binary features for training.

Split data into training and testing sets.

Scaled features and trained a logistic regression model.

Evaluated model using classification report, confusion matrix, and ROC-AUC score.

### 5. Lead Scoring Algorithm
Converted predicted probabilities into a 0–100 score.

Segmented scores into 5 lead categories: Very Hot, Hot, Warm, Cold, and Very Cold.

Assigned suggested actions for each category (e.g., "Call Immediately", "Send Follow-up Email").

## 📂 Files in This Repository
data_leadscoring.csv – Original dataset (not included in public repo for privacy)

code_leadscoring.ipynb – Jupyter Notebook with complete code

cleaned_leads.csv – Cleaned version of the dataset

lead_scoring_output.csv – Final output with scores, categories, and suggested actions

README.md – Project documentation
