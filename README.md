# ABC-Company-Employee-Analysis

Employee Data Analysis using Python, Pandas, NumPy, Matplotlib and Seaborn.

## Project Overview

This project focuses on analyzing employee data from ABC Company using Python. The dataset consists of 458 employee records and 9 columns.

The main objective is to perform data preprocessing and exploratory data analysis (EDA), identify patterns in employee distribution and salary expenditure, and represent the findings through graphical visualizations.

## Technologies and Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook (Google Colab)

## Dataset Description

The dataset contains employee information with the following columns:

- Name
- Team
- Number
- Position
- Age
- Height
- Weight
- College
- Salary

**Dataset Size:** 458 rows and 9 columns.

## 1. Data Preprocessing

The following preprocessing steps were performed:

- Imported the dataset using Pandas.
- Inspected the dataset structure and columns.
- Checked for missing values and data consistency.
- Replaced the existing values in the Height column with randomly generated integers between 150 and 180 using NumPy, as specified in the assignment.
- Verified the updated Height column.

## 2. Analysis Tasks

### Task 1: Employee Distribution Across Teams

Calculated the number of employees in each team and their percentage contribution to the total workforce.

**Key Findings:**
- Employees are distributed across 30 different teams.
- New Orleans Pelicans has the highest number of employees, with 19.
- Orlando Magic and Minnesota Timberwolves have the lowest number, with 14 each.

**Visualization:** Bar Chart.

### Task 2: Employee Distribution Based on Position

Grouped employees based on their positions and calculated the employee count for each position.

**Key Findings:**
- The dataset contains five positions: SG, PF, PG, SF and C.
- SG has the highest number of employees, with 102.
- C has the lowest number of employees, with 79.

**Visualization:** Count Plot.

### Task 3: Predominant Age Group

Categorized employees into different age groups and identified the age group with the highest number of employees.

**Key Findings:**
- The predominant age group is 18–25 years, with 200 employees.
- The majority of employees belong to the younger age groups.

**Visualization:** Bar Chart.

### Task 4: Salary Expenditure Analysis

Calculated salary expenditure across teams and positions to identify the team-position combination with the highest expenditure.

**Key Findings:**
- Los Angeles Lakers – SF has the highest salary expenditure.
- The total salary expenditure is $31,866,445.

**Visualization:** Horizontal Bar Chart.

### Task 5: Correlation Between Age and Salary

Analyzed the relationship between employee age and salary using correlation analysis.

**Key Findings:**
- The correlation coefficient is approximately 0.214.
- Age and salary have a weak positive correlation.
- Age alone does not strongly explain salary differences.

**Visualization:** Scatter Plot with Regression Line.

## 3. Data Visualizations

The following graphical representations were created using Matplotlib and Seaborn:

- Bar Chart – Employee distribution across teams.
- Count Plot – Employee distribution by position.
- Bar Chart – Employee distribution by age group.
- Horizontal Bar Chart – Salary expenditure by team and position.
- Scatter Plot with Regression Line – Correlation between age and salary.

## 4. Overall Insights

- Employee distribution is relatively balanced across the 30 teams.
- SG is the most common position.
- The predominant age group is 18–25 years.
- Los Angeles Lakers – SF has the highest salary expenditure.
- Age and salary have a weak positive correlation.

## 5. Conclusion

This project provided an opportunity to explore employee data analysis using Python. Through data preprocessing and exploratory data analysis, meaningful insights were identified regarding employee distribution, positions, age groups, and salary expenditure. The visualizations helped represent the findings clearly and understand patterns within the dataset.
