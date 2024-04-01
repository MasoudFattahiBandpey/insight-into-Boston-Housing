# Insights into Boston Housing: An Analytical Dive into Value Determinants

## Project Overview
This project aims to uncover the dynamics influencing housing prices in Boston, utilizing a dataset derived from the U.S. Census Service. Through statistical analysis and visualization, we explore several factors such as proximity to the Charles River, age of properties, nitric oxide concentrations, and distance to employment centers to understand their impact on the median value of owner-occupied homes.

### Key Questions Addressed:
1. Does proximity to the Charles River affect housing prices?
2. How do the age of homes and the proportion of owner-occupied units built prior to 1940 influence their value?
3. Is there a relationship between nitric oxide concentrations and the proportion of non-retail business acres per town?
4. What impact does the weighted distance to the five Boston employment centres have on housing prices?

## Dataset Description
The dataset contains several variables, including:
- `CRIM`: Per capita crime rate by town
- `ZN`: Proportion of residential land zoned for lots over 25,000 sq.ft.
- `INDUS`: Proportion of non-retail business acres per town
- `CHAS`: Charles River dummy variable (1 if tract bounds river; 0 otherwise)
- `NOX`: Nitric oxides concentration (parts per 10 million)
- `RM`: Average number of rooms per dwelling
- `AGE`: Proportion of owner-occupied units built prior to 1940
- `DIS`: Weighted distances to five Boston employment centres
- `RAD`: Index of accessibility to radial highways
- `TAX`: Full-value property-tax rate per $10,000
- `PTRATIO`: Pupil-teacher ratio by town
- `LSTAT`: % lower status of the population
- `MEDV`: Median value of owner-occupied homes in $1000's

## Tools and Technologies Used
- Python: For data manipulation and analysis
- Pandas: For data processing and CSV file I/O
- Matplotlib and Seaborn: For data visualization
- SciPy and StatsModels: For conducting statistical tests

## Setup and Installation
Ensure you have Python 3.x installed on your system. It is also recommended to use a virtual environment. Install the project dependencies with:

```bash
pip install -r requirements.txt
