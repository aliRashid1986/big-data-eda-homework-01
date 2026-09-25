# Titanic Dataset - Exploratory Data Analysis

## Course
Big Data Analysis

## Objective
Perform exploratory data analysis on the Titanic dataset using Python, Pandas, Matplotlib, and Seaborn.

## Dataset Source
Titanic dataset from seaborn-data.

## Main Findings
- The dataset contains 891 rows.
- The original dataset contained 15 columns.
- After data cleaning, the dataset contains 14 columns.
- The `deck` column was removed because approximately 77.22% of its values were missing.
- There were 107 duplicate rows, which were retained because the dataset does not contain a unique passenger identifier.
- Female passengers had a higher survival rate than male passengers.
- First-class passengers had a higher survival rate than second- and third-class passengers.
- Correlation analysis showed relationships between several numerical variables.

## Data Cleaning
- Missing `age` values were replaced using the median age calculated separately for each sex.
- Missing `embarked` and `embark_town` values were replaced using the mode.
- The `deck` column was removed because of its high percentage of missing values.
- Duplicate rows were retained because identical rows could not be confirmed as duplicate passengers.

## Requirements
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

## How to Run
1. Download or clone this repository.
2. Open Jupyter Notebook.
3. Open `EDA_Homework.ipynb`.
4. Make sure `dataset.csv` is in the same folder as the notebook.
5. Run all cells.

## Conclusion
The exploratory analysis identified differences in survival rates by sex and passenger class and revealed several relationships among numerical variables. The results represent associations in the dataset and do not establish causation.
