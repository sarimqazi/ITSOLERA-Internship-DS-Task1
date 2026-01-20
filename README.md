# Task 1: Data Handling with NumPy & Pandas

## Task Objective
The primary objective of this task is to perform data handling and analysis on a student performance dataset. The goal is to utilize Python libraries such as **Pandas** and **NumPy** to load, clean, and analyze the data to understand the structure and categorical distributions within the dataset.

## Approach
The analysis followed a standard data handling process:

1.  **Data Loading**:
    -   Imported necessary libraries: `pandas`, `numpy`, `matplotlib.pyplot`, `seaborn`, and `sklearn`.
    -   Loaded the dataset (`Student_Performance.csv`) into a Pandas DataFrame.
    -   Displayed the first few rows to understand the data schema.
2.  **Data Inspection**:
    -   **Shape Analysis**: Checked the number of rows and columns to assess dataset size.
    -   **Structure Analysis**: Used `.info()` to view data types and check for null values.
    -   **Statistical Summary**: Applied `.describe()` to obtain summary statistics (mean, std, min, max) for numerical columns.
3.  **Data Analysis**:
    -   Analyzed categorical variables to understand the frequency and distribution of non-numeric data.
    -   Performed specific column-based operations to filter or investigate data subsets.

## Results and Insights
-   **Dataset Overview**: Properly loaded and structured the student performance data for analysis.
-   **Data Quality**: Verified data integrity by checking for valid entries and data types.
-   **Statistical Distribution**: Gained insights into the central tendencies and spread of the numerical features (e.g., scores, hours studied).
-   **Structure**: Established a cleaned and understood baseline for further predictive modeling or advanced visualization.
