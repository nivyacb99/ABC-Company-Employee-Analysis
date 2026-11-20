# ABC Company Employee Data Analysis

## Project Overview

This project focuses on analyzing employee data from ABC Company using Python. The objective is to explore employee demographics, team distribution, job positions, and salary expenditure through data preprocessing, statistical analysis, and visualizations.

The analysis helps identify patterns in employee distribution, understand workforce demographics, and compare salary expenditure across teams and positions.

## Dataset Description

- **Dataset Name:** ABC Company Employee Dataset
- **Number of Records:** 458
- **Number of Columns:** 9

The dataset contains employee-related information, including team, position, age, salary, and other attributes.

## Data Preprocessing

The following preprocessing steps were performed to prepare the dataset for analysis:

- Imported the dataset using Pandas.
- Inspected the dataset structure, column names, data types, and basic information.
- Checked the dataset for missing values and data consistency.
- Replaced the values in the `height` column with random numbers between 150 and 180, as specified in the project requirements.

## Analysis Performed

### 1. Employee Distribution Across Teams
Analyzed the number of employees in each team and calculated the percentage of employees in each team relative to the total workforce.

### 2. Employee Segregation by Position
Grouped employees based on their positions to understand the workforce distribution across different job roles.

### 3. Age Group Analysis
Categorized employees into age groups and identified the age group with the highest number of employees.

### 4. Salary Expenditure Analysis
Analyzed total salary expenditure across teams and positions to identify the team and position with the highest salary expenditure.

### 5. Age and Salary Correlation
Investigated the relationship between employee age and salary using correlation analysis to understand whether salary tends to vary with age.

## Graphical Representations

The analysis was supported by the following visualizations:

- **Employee Distribution by Team:** Visualized employee count and percentage distribution across teams.
- **Employee Distribution by Position:** Represented the number of employees in each position.
- **Employee Distribution by Age Group:** Displayed employee distribution across different age groups.
- **Salary Expenditure by Team:** Compared total salary expenditure across teams.
- **Salary Expenditure by Position:** Compared total salary expenditure across positions.
- **Age vs. Salary Scatter Plot:** Visualized the relationship between employee age and salary.

## Key Insights

- Employee distribution across teams is relatively balanced.
- Shooting Guards (SG) have the highest representation among positions.
- The 22–25 age group has the highest number of employees, indicating a relatively young workforce.
- Cleveland Cavaliers have the highest total salary expenditure among teams.
- Centers (C) account for the highest total salary expenditure among positions.
- Age and salary have a weak positive correlation, indicating that age alone does not strongly explain salary differences.

## Data Story

The analysis reveals a relatively balanced workforce distribution across teams, with a higher representation of employees in Shooting Guard and Power Forward positions. The workforce is predominantly concentrated in the younger age groups, particularly between 22 and 25 years.

Salary expenditure varies across teams and positions, with the Cleveland Cavaliers recording the highest team expenditure and Centers contributing the highest position-wise expenditure. The correlation analysis indicates a weak positive relationship between age and salary, suggesting that other factors may also influence salary differences.

Overall, the analysis provides a clear overview of workforce distribution, age demographics, and salary patterns within the organization.

## Tools and Technologies Used

- **Python** – Programming and data analysis
- **Pandas** – Data manipulation and analysis
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical visualization
- **Google Colab** – Development environment
- **Jupyter Notebook** – Interactive analysis and documentation




