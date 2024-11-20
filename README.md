
# Python Case Study: Data Analysis

This project demonstrates essential data analysis techniques, including data cleaning, univariate and bivariate analysis, and memory optimization, using Python and Pandas. It provides a step-by-step approach to extracting insights from a dataset.

---

## 🚀 **Project Overview**

### Key Features:
- **Data Cleaning**:
  - Replace missing values and handle duplicates.
  - Optimize memory usage by changing data types.
- **Exploratory Data Analysis (EDA)**:
  - Univariate and Bivariate analysis of key variables.
  - Visualization and summary statistics.
- **Data Transformations**:
  - Replace categorical values with numerical labels.
  - Convert data types for optimization.

---

## 📂 **Dataset**

- **Dataset**: The dataset used in this project contains demographic and income data.
- **Size**: Number of rows and columns may vary based on data cleaning and processing.

---

## 🔧 **Questions Addressed**
The analysis answers the following questions:

1. Display the top 10 rows of the dataset.
2. Check the last 10 rows of the dataset.
3. Find the shape of the dataset (number of rows and columns).
4. Get detailed information about the dataset, including memory usage.
5. Fetch a 50% random sample from the dataset.
6. Check for missing values.
7. Perform data cleaning by replacing `?` with `NaN`.
8. Drop rows with missing values.
9. Check for duplicate data and drop duplicates.
10. Get overall statistics about the dataset.
11. Drop unnecessary columns: `education-num`, `capital-gain`, and `capital-loss`.
12. Analyze the distribution of the `age` column.
13. Find the total number of persons aged between 17 and 48.
14. Analyze the distribution of the `workclass` column.
15. Count persons with Bachelor's and Master's degrees.
16. Perform bivariate analysis.
17. Replace salary values with binary labels (0 and 1).
18. Identify which `workclass` has the highest salary.
19. Determine whether males or females are more likely to earn a salary >50K.
20. Convert the `workclass` column datatype to `category`.

---

## 📜 **Methods and Functions Used**
### Key Python Functions:
- `isin()`
- `between()`
- `unique()`
- `dropna()`
- `replace()`
- `duplicated()`
- `drop_duplicates()`
- `astype()`
- `apply()`

### Analysis Techniques:
- **Univariate Analysis**: Focuses on individual column distributions.
- **Bivariate Analysis**: Explores relationships between two variables.

### Memory Optimization:
- Reduced memory usage by converting columns to appropriate data types (e.g., `category`).

---

## 🛠️ **Technologies Used**
- **Python**: Core programming language for analysis.
- **Pandas**: Data manipulation and cleaning.
- **Matplotlib/Seaborn**: For visualizations (if applicable).
- **Jupyter Notebook**: For running and documenting the analysis interactively.

---

## 📈 **Results and Insights**
### Key Findings:
- Identified and removed duplicate and missing data to improve data quality.
- Found the distribution and relationship of key variables (e.g., `age`, `workclass`).
- Males have a higher probability of earning >50K compared to females.
- The `Private` workclass has the highest number of high-salary individuals.

---

