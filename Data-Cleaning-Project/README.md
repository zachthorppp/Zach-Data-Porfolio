# Extensive Data Cleaning and Exploratory Data Analysis (EDA)

## Overview
This project focuses on the process of preparing extremely messy raw data for analysis and uncovering insights through exploratory techniques. Using Python, I cleaned a real-world dataset and performed EDA to explore trends, detect outliers, and uncover patterns that could inform business decisions.

## Objective
To demonstrate a structured, replicable approach to cleaning messy data and applying statistical and visual exploration techniques to understand key features and relationships within the dataset.

## Tools and Libraries
- Python (Jupyter Notebook)
- `pandas` for data wrangling
- `numpy` for numerical operations
- `matplotlib` and `seaborn` for visualisation
- `missingno` for missing data analysis
- `sklearn.preprocessing` for transformations

## Folder Structure

```
Data-Cleaning-Project/
├── Extensive Data Cleaning and EDA.ipynb               # Jupyter notebook with cleaning and EDA code
├── README.md                                           # Project documentation
└── Visuals/                                            # Supporting files and visualisations
├── Box Plot Example .png                               # Box plot highlighting outliers
├── Categorical Analysis Example.png                    # Visual analysis of categorical data
├── Cleaning Activities Identification.png              # Annotated cleaning steps
├── Correlation Matrixx.png                             # Heatmap showing variable correlations
├── Exploratory PairPlot Analysis.png                   # Pairplot of key features
├── MutliCollinearity Checking.xlsx                     # VIF/collinearity checks
└── Random Forest Feature Selection.png                 # Feature importance ranking
```

## Process

### 1. Data Inspection
- Loaded the dataset and reviewed shape, columns, data types
- Identified missing values, duplicates, and inconsistent formats

### 2. Data Cleaning
- Handled missing data (e.g., imputation, row removal)
- Converted data types and corrected inconsistencies
- Removed duplicates and cleaned categorical values
- Detected and managed outliers
- Dealt with impossible values

### 3. Exploratory Data Analysis (EDA)
- Correlation analysis to identify relationships between variables
- Bivariate visual exploration using:
  - Boxplots
  - Heatmaps
  - Pairplots
- Categorical vs numerical comparisons

### 4. Insights
- Data needed extensive cleaning and preparation
- Identified multicollinearity in the data
- Highlighted key features contributing to variance
- Flagged potential feature engineering opportunities for modelling

## Key Visuals

- [Box Plot Example](Visuals/Box%20Plot%20Example.png)
- [Correlation Matrix](Visuals/Correlation%20Matrixx.png)
- [PairPlot](Visuals/Exploratory%20PairPlot%20Analysis.png)
- [Categorical Analysis](Visuals/Categorical%20Analysis%20Example.png)
- [Cleaning Activities](Visuals/Cleaning%20Activities%20Identification.png)
- [Feature Importance](Visuals/Random%20Forest%20Feature%20Selection.png)


## Outcome
This project reinforced my understanding of practical data preparation and highlighted the importance of thorough EDA in shaping future modelling decisions. It would be a foundational step in a machine learning pipeline.

## Next Steps
- Feature engineering for model preparation
- Model selection and evaluation
- Automate data profiling

## [Link to Notebook (if on GitHub)](https://github.com/your-repo/Extensive-Data-Cleaning-EDA)
