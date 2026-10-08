# House Price Prediction

A machine learning project that analyzes housing data and builds a model to predict house prices based on relevant property features.

## Project Overview

The goal of this project is to understand housing data, perform exploratory data analysis, prepare features, and build a machine learning model for house price prediction.

The project follows a complete machine learning workflow:

1. Data Understanding
2. Exploratory Data Analysis (EDA)
3. Feature Engineering
4. Model Training
5. Model Evaluation

## Project Structure

```text
house-price-prediction/
│
├── notebooks/
│   ├── 01_Data_Understanding.ipynb
│   ├── 02_EDA.ipynb
│   └── 03_Feature_Engineering_Model_Training.ipynb
│
├── README.md
└── requirements.txt
```

## Dataset

- Records: 50,000
- Features: 19
- Target: House Price

The dataset is used to analyze the factors associated with house prices and develop a predictive machine learning model.

## Workflow

### 1. Data Understanding

The first notebook focuses on understanding the dataset, including:

- Dataset dimensions
- Data types
- Missing values
- Duplicate records
- Statistical summary
- Target variable
- Feature distributions

### 2. Exploratory Data Analysis

The EDA notebook explores relationships and patterns in the housing data using visualizations and statistical analysis.

Key activities include:

- Univariate analysis
- Bivariate analysis
- Correlation analysis
- Distribution analysis
- Identification of important patterns and outliers

### 3. Feature Engineering & Model Training

The final notebook prepares the data for machine learning and trains the prediction model.

Activities include:

- Feature preparation
- Data transformation
- Train-test split
- Model training
- Prediction
- Model evaluation

## Model

### Linear Regression

Linear Regression was used as the machine learning model for predicting house prices.

### Model Performance

| Metric | Result |
|---|---:|
| R² Score | ~0.913 |
| MAE | ~2,260,258 |
| RMSE | ~3,184,755 |

> The reported results are based on the current project notebook.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Key Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis
- Data Visualization
- Feature Engineering
- Machine Learning
- Model Evaluation
- Python Data Analysis

## How to Use

Clone the repository and open the notebooks using Jupyter Notebook or JupyterLab.

```bash
git clone https://github.com/Venukrishnan-21/house-price-prediction.git
```

Then open the notebooks in the `notebooks` folder and execute the cells in order.

## Project Status

Completed
