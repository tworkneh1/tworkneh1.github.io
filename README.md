#   Breast Cancer Analysis 
## Overview
This project explores a breast cancer dataset containing clinical features used to assess tumor progression and lymph node involvement. The goal is to perform exploratory data analysis (EDA), visualize trends, and evaluate relationships between tumor characteristics and staging.

# The Dataset Overview
The dataset containes 4,024 rows and 16 variables, including:
- T Stage: classification based on tumor size and extent
- N Stage: level of spread to nearby lymph nodes
- Grade: degree of differentiotion of cancer cells
- Survival Months: survival months after the initial diagnosis
- Tumor Size: size of the tumor
- additional demographic (age, race, and marital status) and other clinical features
These features provide meaningful insights into cancer progression and are used throughout the analysis to identify trends and potential predictors.

# Technologies Used 
- Python
- Pandas, ydata_profiling
- seaborn
- matplotlib
- sweetviz
- jupyter
  
# Data Cleaning and Statistical Analysis
Before conducting the analysis, the dataset was cleaned to ensure accuracy and consistency. This included:
- Identifying and removing variables with excessive null values
- Dropping records with missing data when appropriate
- Checking for inconsistent or out-of-range values
- Standardizing categorical variables (e.g., T stage, N stage, grade)

# Statistical Description
After cleaning, descriptive statistics were used to better understand the structure and distribution of the data. Summary methods included:
- pandas.DataFrame.describe() for numerical and categorical features
- Distribution checks (mean, median, standard deviation)
- Value counts for key categorical staging variables

# EDA Highlights
- Visualizations exploring the distribution of tumor stages
- relationships between variables
- Identification of trends in diagnosis across age groups
- Heatmaps and correlation analysis using seaborn and sweetviz 

# Project Goals
- Understand patterns in breast cancer staging
- Identify relationships among tumor characteristics
- Development of predictive models for staging or risk classification


