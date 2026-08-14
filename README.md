# 202618039_lab-02

# DS605: Fundamentals of Machine Learning

## Lab Assignment 2

 Vectorized Programming with NumPy and Data Wrangling with Pandas



## Dataset

Kaggle Titanic Dataset (train.csv)

## Objective

The objective of this assignment is to practice vectorized NumPy operations and basic data wrangling with Pandas using the Titanic dataset.

## Part A: Vectorized Programming with NumPy

### Task 1: Arrays, Statistics, and Indexing

- Generate an array of 100 random integers using a random seed.
- Calculate minimum, maximum, median, mean, and standard deviation.
- Generate an array using `np.arange()`.
- Implement `np.zeros()` and `np.ones()`.
- Implement `np.linspace()` and compare it with `np.arange()`.
- Create and manipulate 2D and 3D arrays.
- Perform indexing, row selection, column selection, and slicing.
- Use reshape() and flatten().

### Task 2: Vectorized Arithmetic and Linear Algebra

- Create two matrices.
- Perform matrix addition.
- Perform element-wise multiplication.
- Perform matrix multiplication using @.
- Calculate the transpose of a square matrix.
- Calculate the determinant.
- Calculate the inverse of an invertible matrix.
- Verify the inverse using np.allclose().
- Use vectorized NumPy operations without explicit Python loops.

### Task 3: Normal Distribution and Histogram

- Generate at least 1,000 values from a normal distribution.
- Calculate the sample mean and sample standard deviation.
- Compare the sample statistics with the chosen mean and standard deviation.
- Plot a histogram of the generated data.

## Part B: Data Wrangling with Pandas

### Task 4: Load and Inspect Data

- Load the Titanic train.csv dataset.
- Inspect the data using head(),tail(), shape, columns, info(), and describe().
- Use loc and iloc for selecting rows and columns.

### Task 5: Filtering and Querying

The following questions are answered using Boolean indexing and/or query():

- Count male passengers older than 50.
- Find the number of female first-class passengers and their survival percentage.
- Find passengers aged 20–40 with Fare above the overall median who survived.
- Find passengers travelling alone, aged below 30, who did not survive.
- Find passengers who embarked from Southampton, were in Pclass 2 or 3, and paid more than the Southampton median Fare.

### Task 6: GroupBy and Aggregation

- Calculate survival rate by Sex.
- Calculate survival rate by Pclass.
- Calculate average Age and Fare by Pclass.
- Calculate passenger count and survival rate by Sex-Pclass.
- Calculate passenger count, average Fare, and survival rate by Embarked.

### Task 7: Missing Values and Fare Outliers

- Calculate missing-value count and percentage for every column.
- Plot missing-value counts.
- Fill missing Age values using the mean Age.
- Compare mean, median, mode, and random-value imputation.
- Calculate Q1, Q3, IQR, and 1.5 × IQR bounds for Fare.
- Identify and count Fare outliers.

### Task 8: Features and Pivot Table

- Create FamilySize = SibSp + Parch + 1.
- Create IsAlone based on FamilySize.
- Create a pivot table with Sex as rows, Pclass as columns, and mean Survived as values.
- Identify the highest and lowest survival groups.

### Task 9: Visualizations and Observations

- Create a correlation heatmap for relevant numerical columns.
- Plot survival rate by Sex.
- Plot Age versus Fare and distinguish between survived and non-survived passengers.
- Write 5–7 observations based on numerical results and visualizations.

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook



## Key Observations

The final observations will be based on the numerical results and visualizations obtained from the Titanic dataset analysis.

1. The sample statistics of the generated normal distribution are close to the selected mean and standard deviation.
2. The histogram of the generated normal-distribution data shows an approximately bell-shaped distribution.
3. Survival rates differ between male and female passengers.
4. Survival rates vary across different passenger classes.
5. The Titanic dataset contains missing values that require appropriate handling.
6. The Fare variable contains outliers based on the 1.5 × IQR method.
7. Survival rates differ across combinations of passenger sex and passenger class.

## Conclusion

This assignment provides practical experience with vectorized programming using NumPy and data wrangling using Pandas. It covers array manipulation, statistical calculations, matrix operations, probability distributions, data filtering, grouping, aggregation, missing-value handling, outlier detection, feature engineering, pivot tables, and visualization.

The Titanic dataset is used to apply these techniques to a real-world dataset and understand relationships between passenger characteristics and survival.

## Files Included

- DS605_Lab2_NumPy_Pandas.ipynb — Complete runnable Jupyter Notebook.
- train.csv — Titanic dataset used for the analysis.
- figures/ — Generated figures and visualizations.
- README.md — Project documentation and assignment details.
