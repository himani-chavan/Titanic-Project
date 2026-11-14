# Titanic Dataset – Exploratory Data Analysis

## Project Overview

This project focuses on exploring and analysing the Titanic dataset using Python and Pandas. The objective is to understand the dataset, perform data cleaning, handle missing values, explore passenger information and identify patterns related to passenger survival.

## Technologies Used

- Python
- Pandas
- Jupyter Notebook
- Matplotlib (for box plot visualisation)

## Dataset

The project uses the Titanic dataset containing passenger-related information such as:

- Passenger ID
- Passenger Class
- Name
- Gender
- Age
- Number of Siblings/Spouses
- Number of Parents/Children
- Ticket Information
- Fare
- Cabin
- Embarked Port
- Survival Status

## Project Workflow

### 1. Data Loading and Exploration
- Loaded the dataset using Pandas.
- Inspected records using `head()`, `tail()` and `sample()`.
- Checked dataset dimensions using `shape`.
- Examined column information using `info()` and `dtypes`.
- Generated statistical summaries using `describe()`.

### 2. Statistical Analysis
- Calculated mean, median and mode.
- Explored numerical columns.
- Used box plots to identify potential outliers.

### 3. Data Cleaning
- Identified missing values using `isnull()`.
- Handled missing Age values using median imputation.
- Handled missing Embarked values using mode imputation.
- Checked missing-value counts after cleaning.

### 4. Data Manipulation
- Selected specific rows and columns.
- Applied filtering conditions based on age, gender and survival status.
- Sorted records using `sort_values()`.
- Analysed categorical columns using `unique()`, `nunique()` and `value_counts()`.
- Applied mapping operations to transform Embarked categories.

## Key Learning Outcomes

- Understanding dataset structure and data types.
- Performing exploratory data analysis.
- Handling missing values.
- Applying statistical functions.
- Identifying potential outliers.
- Filtering, sorting and transforming datasets.
- Gaining practical experience with Python and Pandas.

## Project Structure

```text
Titanic-Data-Analysis/
│
├── Titanic Project.ipynb
├── titanic_dataset.csv
└── README.md
```

## How to Run the Project

1. Clone or download this repository.
2. Install the required Python libraries:

```bash
pip install pandas matplotlib jupyter
```

3. Open Jupyter Notebook:

```bash
jupyter notebook
```

4. Open `Titanic Project.ipynb`.
5. Run the notebook cells sequentially.

**Note:** Keep the dataset file in the same directory as the notebook, or update the dataset file path accordingly.

## Conclusion

This project provided practical experience in data exploration, statistical analysis, data cleaning and manipulation using Python. It helped strengthen my understanding of Pandas and the fundamentals of exploratory data analysis.
