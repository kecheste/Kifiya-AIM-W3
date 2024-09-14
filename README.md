# Insurance Claim Analysis - Task 1

## Project Overview

This project is part of my role as a Marketing Analytics Engineer at AlphaCare Insurance Solutions (ACIS). The goal of this project is to analyze historical car insurance claim data and provide insights that will help optimize marketing strategies and identify low-risk clients for potential premium reductions.

In **Task 1**, the focus is on setting up version control with Git, performing exploratory data analysis (EDA) to understand the data, and implementing statistical techniques to uncover actionable insights. This README provides an overview of the setup, tools, and methodology used for Task 1.

## Repository Structure

- `task-1/`: All code and notebooks related to Task 1.
- `.github/workflows/`: Configuration for CI/CD using GitHub Actions.
- `README.md`: Documentation for the project.
- `data/`: (Optional) Folder to store the dataset.
- `notebooks/`: Jupyter notebooks for EDA and analysis.

## Setup Instructions

### Prerequisites

Before you begin, ensure you have the following installed:

- Python 3.x
- Git
- Required Python packages listed in `requirements.txt`

## Exploratory Data Analysis (EDA)

### Objective

The goal of the EDA is to understand the data, discover patterns, and highlight key insights that could influence marketing and insurance strategies. The analysis includes:

- Data summarization using descriptive statistics.
- Data quality checks to identify missing values and anomalies.
- Univariate and bivariate analysis to explore variable distributions and relationships.
- Visualization of key insights with creative and informative plots.

### Key Steps

1. Data Summarization:

- Calculated descriptive statistics for numerical variables like TotalPremium and TotalClaims.
- Checked data types and ensured that categorical variables and dates were formatted correctly.

2. Univariate Analysis:

- Plotted histograms for numerical variables and bar charts for categorical variables to understand their distributions.

3. Bivariate Analysis:

- Explored relationships between features such as TotalPremium, TotalClaims, PostalCode, and Province.
- Used correlation matrices to identify relationships between numerical features.

4. Outlier Detection:

- Box plots were used to detect outliers in variables like TotalPremium and TotalClaims.

### Key Visualizations

Three key plots were created to illustrate insights from the data:

1. _Correlation heatmap_ for TotalPremium and TotalClaims.
2. _Bar chart_ comparing average premiums across different provinces.
3. _Box plot_ showing outliers in TotalPremium for different vehicle types.

### Statistical Analysis

In addition to the EDA, statistical thinking was applied to understand:

- Variability in insurance premiums and claims.
- Potential correlations and associations between different features like PostalCode, Province, and Gender.

### Future Work

In future tasks, machine learning models will be developed to predict optimal premium values based on car, owner, and location features. Additionally, hypothesis testing will be applied to validate key assumptions about risk differences between different demographics and regions.

### License

This project is licensed under the MIT License - see the LICENSE file for details.
