# Synent Technologies – Task 1: Data Cleaning & Preprocessing

## Problem Statement

The objective of this project is to clean and prepare the Titanic dataset for further analysis.

The main data preprocessing tasks include handling missing values, removing duplicate rows, converting data types, and renaming columns into a consistent format.

## Dataset Details

The project uses the Titanic Dataset.

The original dataset contains:

- 891 rows
- 12 columns
- Missing values in Age, Cabin, and Embarked
- No duplicate rows

The dataset contains information about passengers, including passenger class, name, sex, age, family information, ticket, fare, cabin, and embarkation port.

## Data Cleaning Approach

The following preprocessing steps were applied:

### 1. Handling Missing Values

- Missing values in `Age` were replaced with the median age.
- Missing values in `Embarked` were replaced with the most frequent value.
- Missing values in `Cabin` were replaced with `Unknown`.

### 2. Removing Duplicate Rows

Duplicate rows were checked and removed from the dataset.

### 3. Converting Data Types

Numeric columns were converted to appropriate numeric data types to ensure consistency.

### 4. Renaming Columns

Column names were renamed using a consistent snake_case format.

For example:

- `PassengerId` → `passenger_id`
- `Survived` → `survived`
- `Pclass` → `passenger_class`
- `SibSp` → `siblings_spouses`
- `Parch` → `parents_children`

## Results

After preprocessing:

- Final dataset size: 891 rows × 12 columns
- Missing values: 0
- Duplicate rows: 0
- Column names were standardized
- The cleaned dataset was saved as `titanic_cleaned.csv`

The final dataset is ready for further analysis.

## Files

- `Titanic-Dataset.csv` – Original Titanic dataset
- `titanic_cleaned.csv` – Cleaned and processed dataset
- `Titanic_Data_Cleaning.ipynb` – Jupyter/Google Colab notebook containing the complete preprocessing workflow

## Tools Used

- Python
- Pandas
- Google Colab / Jupyter Notebook
