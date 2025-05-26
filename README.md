# PYTHON-ENTRI FINAL ASSIGNMENT

# ABC Company Employee Analysis Project

## 📌 Project Overview
This project analyzes employee data from ABC Company to provide actionable insights into team composition, position distribution, salary expenditures, and demographic patterns. The dataset contains 458 rows and 9 columns. The final output includes data preprocessing, five analytical tasks, corresponding visualizations, and key insights.


## 🧹 Preprocessing
- Replaced the "Height" column with random integers between 150 and 180 to simulate accurate height data.
- Ensured all relevant columns (`Salary`, `Age`) were cleaned and correctly typed.


## 📊 Analysis Tasks

### 1️⃣ Distribution of Employees Across Teams
- Counted employees per team.
- Calculated each team's share as a percentage of the total.

### 2️⃣ Segregation Based on Positions
- Counted total employees by position.
- **Visualization:** Bar chart.

### 3️⃣ Predominant Age Group
- Categorized ages into defined groups (e.g., 26–30, 31–35).
- Identified the most common age group.
- **Visualization:** Bar chart.

### 4️⃣ Salary Expenditure by Team and Position
- Calculated total salary by team and position.
- Identified the highest-spending team and position.
- **Visualization:** Two bar charts.

### 5️⃣ Correlation Between Age and Salary
- Calculated Pearson correlation coefficient.
- Visualized using scatter plot with regression line.
- **Result:** Correlation value indicated nature of relationship.


## 📈 Graphical Representations
- Used `matplotlib` and `seaborn` for all visualizations.
- Ensured plots were labeled and legible with proper titles and legends.

## 📌 Insights Gained

- Certain teams have significantly more members and higher salary expenditure.
- Management and senior positions contribute most to payroll.
- Age groups between 26–35 are predominant, reflecting a young to mid-career workforce.
- A moderate positive correlation exists between age and salary, suggesting experience impacts compensation.


