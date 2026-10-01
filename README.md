# Lung Cancer Prediction using Machine Learning

A beginner-friendly machine learning project built as my first end-to-end ML classification project.

The project uses a lung cancer survey dataset to explore the data, clean it, perform exploratory data analysis (EDA), and eventually build a machine learning classification model.

> **Project status:** Data loading, data inspection, cleaning, and initial feature-level EDA are complete. Model training and evaluation are the next stage.

## Project Goals

- Understand a real tabular dataset
- Practice data cleaning and preprocessing
- Perform exploratory data analysis
- Identify useful features
- Build a classification model
- Evaluate model performance using appropriate metrics
- Understand the complete ML workflow rather than only calling a model library

## Dataset

The dataset contains survey-style attributes related to lung cancer indicators, including features such as:

- Age
- Gender
- Smoking
- Yellow fingers
- Anxiety
- Peer pressure
- Chronic disease
- Fatigue
- Allergy
- Wheezing
- Alcohol consuming
- Coughing
- Shortness of breath
- Swallowing difficulty
- Chest pain

The target variable is:

`LUNG_CANCER`

## Current Workflow

```text
Raw Dataset
    ↓
Load Dataset
    ↓
Understand Structure
    ↓
Check Missing Values
    ↓
Check Duplicates
    ↓
Clean Dataset
    ↓
Exploratory Data Analysis
    ↓
Feature Analysis
    ↓
Preprocessing
    ↓
Train/Test Split
    ↓
Model Training
    ↓
Model Evaluation
```

## Repository Structure

```text
lung-cancer-prediction-ml/
│
├── data/
│   └── .gitkeep
│
├── notebooks/
│   └── 01_lung_cancer_eda.ipynb
│
├── src/
│   └── .gitkeep
│
├── .gitignore
├── README.md
└── requirements.txt
```

## Notebook

### `01_lung_cancer_eda.ipynb`

The notebook currently covers:

1. Importing NumPy and Pandas
2. Loading the dataset
3. Inspecting dataset shape
4. Checking data types and structure
5. Descriptive statistics
6. Checking missing values
7. Checking class distribution
8. Detecting duplicate rows
9. Creating a cleaned copy of the dataset
10. Removing duplicate records
11. Initial visual analysis
12. Age distribution
13. Age vs. target
14. Gender vs. target
15. Inspecting feature values

## Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Scikit-learn — planned for the modeling stage

## Installation

Clone the repository:

```bash
git clone https://github.com/YOUR-USERNAME/lung-cancer-prediction-ml.git
cd lung-cancer-prediction-ml
```

Create a virtual environment:

```bash
python -m venv .venv
```

Activate it on Windows:

```bash
.venv\Scripts\activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Start Jupyter:

```bash
jupyter notebook
```

## Important Note

This is an educational machine learning project. It is **not a medical diagnostic system** and should not be used to diagnose lung cancer or make clinical decisions.

## Learning Objective

The main purpose of this project is to understand the machine learning workflow from raw data to a trained and evaluated classification model.

