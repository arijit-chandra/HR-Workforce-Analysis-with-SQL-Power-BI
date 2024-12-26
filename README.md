# HR-Workforce-Analysis-with-SQL-Power-BI

This project analyzes and visualizes the distribution of employees within an organization, providing insights into departmental allocations, geographical dispersion, and diversity metrics. The findings inform strategic decisions, optimize resource allocation, and enhance workforce planning.

## Data Used

- **Data:** HR Data with over 22000 rows from the year 2000 to 2020.
- **Data Cleaning & Analysis:** MySQL
- **Data Visualization:** Power BI

## Questions

1. What is the gender breakdown of employees in the company?
2. What is the race/ethnicity breakdown of employees in the company?
3. What is the age distribution of employees in the company?
4. How many employees work at headquarters versus remote locations?
5. What is the average length of employment for employees who have been terminated?
6. How does the gender distribution vary across departments and job titles?
7. What is the distribution of job titles across the company?
8. Which department has the highest turnover rate?
9. What is the distribution of employees across locations by state?
10. How has the company's employee count changed over time based on hire and term dates?
11. What is the tenure distribution for each department?

## Summary of Findings

- **Gender Breakdown:** There are more male employees than female employees in the company. 
    - Male: 8.9K
    - Female: 8.1K
    - Non-Conforming: 0.5K

- **Race/Ethnicity Breakdown:** 
    - White employees comprise the largest racial group.
    - Native Hawaiian and American Indian employees have the lowest representation.

- **Age Distribution:** 
    - The youngest employee is 20 years old, and the oldest is 57 years old.
    - The majority of employees fall within the 25-34 age group (5,000 employees) followed by 35-44 age group. 
    - The 55-64 age group has the lowest representation.

- **Location:** A significant majority of employees work at the headquarters.
    - Headquarters: 74.97%
    - Remote: 25.03%

- **Termination:** The average length of employment for terminated employees is around 7 years.

- **Gender Distribution by Department:** Gender distribution varies across departments, but there is a general trend of more male employees in most departments.

- **Turnover Rate:** **Auditing** has the highest turnover rate (16.00%).

- **Employee Location by State:** A large number of employees reside in Ohio.

- **Employee Count Change:** The company's employee count has increased over the years.

- **Tenure Distribution:** The average tenure for each department is about 8 years, with Legal and Auditing having the highest and Services, Sales, and Marketing having the lowest.

## Limitations

- **Age Data:** Some records had negative ages (967 records), which were excluded from the analysis. The analysis focuses on employees aged 18 years and above.
- **Termination Data:** Some term dates were far into the future (1599 records) and were not included in the analysis. The analysis considers only terminations that have occurred up to the current date.

## Project Workflow

1. **Data Acquisition:** 
    - Obtain the HR dataset.
2. **Data Cleaning and Transformation:**
    - Use MySQL scripts to clean and transform the raw data, handling missing values, inconsistencies, and formatting issues.
3. **Data Analysis:**
    - Execute SQL queries to analyze various aspects of the workforce data, such as age distribution, gender diversity, departmental turnover, location analysis, etc.
4. **Data Visualization:**
    - Create interactive dashboards in Power BI to visualize the key findings and allow for easy exploration of the data.
5. **Documentation:**
    - Write this README file to document the project, its methodology, findings, and insights.

## Skills and Tools

- **Data Analysis:** SQL, Data Cleaning and Transformation
- **Data Visualization:** Power BI
- **Tools:** MySQL, Power BI Desktop

## Contributing

Contributions are welcome! Please feel free to fork the repository and submit pull requests.

## License

This project is licensed under the MIT License.
