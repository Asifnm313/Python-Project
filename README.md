# ABC COMPANY EMPLOYEE DATA ANALYSIS PROJECT

## Overview
This project involves analyzing a dataset from ABC company consisting of **458 rows** and **9 columns**. The goal is to preprocess the dataset, conduct insightful analysis, and present the findings graphically to understand employee distribution, salary trends, and correlations.

---

## Project Objectives
1. **Preprocessing**:
   - Correct the "height" column by replacing its values with random numbers between **150 and 180**.
   - Ensure data consistency and integrity.

2. **Analysis Tasks**:
   - **Task 1**: Determine the distribution of employees across each team and calculate the percentage split relative to the total employees.
   - **Task 2**: Categorize employees based on their positions within the company.
   - **Task 3**: Identify the predominant age group among employees.
   - **Task 4**: Find which team and position incur the highest salary expenditure.
   - **Task 5**: Investigate correlations between age and salary, and represent them visually.

3. **Graphical Representation**:
   - Create effective visualizations for all five analysis tasks.

4. **Data Story**:
   - Summarize findings, highlight key trends, and identify patterns and correlations.

---

## Dataset Description
The dataset includes the following columns:
- **Name**: Name of the employee.
- **Team**: Team/department the employee belongs to.
- **Number**: Assigned employee number.
- **Position**: Job position of the employee.
- **Age**: Age of the employee.
- **Height**: Height of the employee (to be corrected during preprocessing).
- **Weight**: Weight of the employee.
- **College**: College from which the employee graduated.
- **Salary**: Annual salary of the employee.

---

## Deliverables
### Preprocessing
- Replace the invalid "Height" column values with random numbers between **150 and 180**.

### Analysis Tasks
1. **Team Distribution**:
   - Determine the number and percentage of employees in each team.
   - Create a **bar chart** or **pie chart** to visualize team distributions.
   
2. **Position Segregation**:
   - Count employees in each position.
   - Represent findings using a **horizontal bar chart**.

3. **Age Group Analysis**:
   - Define age group ranges (e.g., 20-30, 31-40).
   - Identify the predominant age group and visualize it with a **histogram** or **bar chart**.

4. **Salary Analysis**:
   - Aggregate salary expenditure by team and position.
   - Highlight the team and position with the highest salary expenditure using a **stacked bar chart** or **heatmap**.

5. **Correlation Analysis**:
   - Investigate the relationship between age and salary.
   - Display the correlation with a **scatter plot** and regression line.

### Data Story
- Highlight key trends, patterns, and correlations discovered during the analysis:
  - **Team Distribution**: Identify the most and least populated teams.
  - **Position Insights**: Determine roles with the highest representation and average salaries.
  - **Age Trends**: Provide insights into the age demographics of the workforce.
  - **Salary Trends**: Uncover high-spending teams and roles.
  - **Correlations**: Explain the relationship between age and salary.

---

## Tools and Technologies
- **Programming Language**: Python
- **Libraries**:
  - `Pandas` for data manipulation and analysis.
  - `Matplotlib` and `Seaborn` for data visualization.
  - `Numpy` for numerical operations.
- **Development Environment**: Jupyter Notebook or IDE of your choice.
