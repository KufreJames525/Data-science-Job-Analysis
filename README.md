# Data Science Job Salary Analysis

## Project Overview

This project explores salary trends and variations in data science jobs based on anonymized data from various sources, including surveys, job postings, and public records. The analysis provides insights into salary distributions across experience levels, company size, work location, remote work ratio, and other factors that impact data science compensation. This information can be valuable for benchmarking salaries, career planning, and understanding salary trends in the data science field.

![](https://github.com/KufreJames525/Data-science-Job-Analysis/blob/main/istockphoto-1480239219-612x612.jpg?raw=true)

### Key Objectives
- Analyze overall salary trends in data science jobs over recent years.
- Understand the impact of experience level, company size, employment type, and remote work on salary.
- Visualize salary differences across employee and company locations.
- Provide insights for individuals and organizations for benchmarking and career decision-making.

---

## Table of Contents

1. [Data Collection and Preparation](#data-collection-and-preparation)
2. [Exploratory Data Analysis](#exploratory-data-analysis)
    - [Data Overview](#data-overview)
    - [Descriptive Statistics](#descriptive-statistics)
    - [Salary Trends by Year](#salary-trends-by-year)
    - [Salary by Experience Level](#salary-by-experience-level)
    - [Salary by Employment Type](#salary-by-employment-type)
    - [Company Size Impact on Salary](#company-size-impact-on-salary)
    - [Remote Work and Salary](#remote-work-and-salary)
    - [Geographic Analysis](#geographic-analysis)
3. [Key Findings](#key-findings)
4. [Limitations and Future Work](#limitations-and-future-work)
5. [Conclusion](#conclusion)

---

## Data Collection and Preparation

- **Data Source**: This anonymized dataset was collected from various sources, including surveys, job postings, and public records. The data set was collect from kaggle.
- **Data Description**: The dataset consists of the following columns:
    - `work_year`: Year of data collection.
    - `experience_level`: Level of experience (e.g., entry-level, mid-level).
    - `employment_type`: Type of employment (full-time, part-time, contract).
    - `job_title`: Job title in the data science field.
    - `salary`: Salary in the local currency.
    - `salary_currency`: Currency of the salary.
    - `salary_in_usd`: Salary converted to USD.
    - `employee_residence`: Employee’s residence location.
    - `remote_ratio`: Percentage of work done remotely.
    - `company_location`: Company location.
    - `company_size`: Company size (small, medium, or large).

---

## Exploratory Data Analysis

### Data Overview
- Reviewed the structure and data types of each column.
- Checked for missing values and identified any columns that required cleaning or preprocessing.

### Descriptive Statistics
Calculated basic descriptive statistics to understand the range, average, and spread of salaries, especially `salary_in_usd`, as this is used for comparisons across locations and demographics.

### Salary Trends by Year
- **Objective**: Examine how average salaries have changed over the years.
- **Method**: Calculated the mean salary in USD for each year and created a line chart to visualize the trends.
- **Result**: Displayed an upward or downward trend of data science salaries over recent years.

### Salary by Experience Level
- **Objective**: Understand how salary varies by experience level.
- **Method**: Created a box plot showing the distribution of salaries for each experience level (entry, mid, senior).
- **Result**: Provided insights into the expected salary range at different experience levels, showing how experience influences pay.

### Salary by Employment Type
- **Objective**: Investigate salary differences by employment type.
- **Method**: Created a box plot comparing salary distributions for full-time, part-time, and contract positions.
- **Result**: Identified salary patterns and variations among different employment types.

### Company Size Impact on Salary
- **Objective**: Determine if there is a relationship between company size and salary.
- **Method**: Used a box plot to compare salaries across company sizes (small, medium, and large).
- **Result**: Showed how salaries are impacted by the size of the company, providing benchmarks for job-seekers in small versus large organizations.

### Remote Work and Salary
- **Objective**: Analyze the relationship between remote work ratios and salary.
- **Method**: Visualized salary distributions across different remote work ratios (0%, 50%, 100%).
- **Result**: Offered insights into how remote work options might influence salary in the data science field.

### Geographic Analysis
#### 1. Average Salary by Employee Residence
   - **Objective**: Examine how salary varies by the residence location of employees.
   - **Method**: Calculated average salary in USD for each residence location and created a bar plot for the top 10 locations.
   - **Result**: Highlighted the highest and lowest average salaries by location, providing insight into regional salary variations.

#### 2. Average Salary by Company Location
   - **Objective**: Understand salary variations by company location.
   - **Method**: Created a bar plot for the top 10 company locations by average salary.
   - **Result**: Showed the locations with the highest-paying data science jobs.

---

## Key Findings

1. **Rising Salaries**: Data science salaries have shown an upward trend over recent years, reflecting the growing demand for data science expertise.
2. **Experience-Level Differences**: Higher experience levels correlate with significantly higher salaries.
3. **Company Size Influence**: Large companies tend to offer higher salaries compared to small and medium-sized companies.
4. **Remote Work Premium**: Jobs with a high remote ratio showed varying salary trends, indicating flexibility may play a role in compensation.
5. **Regional Variations**: There are substantial regional variations in salaries, with some countries and cities offering significantly higher pay for data science roles.

---

## Limitations and Future Work

- **Limitations**: The dataset may lack representation for some regions or demographic factors. Also, the data is historical and may not capture the latest trends.
- **Future Work**: Additional analyses could explore salary trends within specific job titles, industry-specific salary variations, and predictive modeling to forecast future salary trends based on current data.

---

## Conclusion

This analysis provided valuable insights into salary trends and factors influencing compensation in the data science job market. By understanding these trends, individuals and organizations can make more informed decisions about job offers, salary expectations, and hiring strategies in the data science field.

---

### Project Code and Notebook

All project code, analysis, and visualizations can be found in the Jupyter Notebook in this repository.

---

