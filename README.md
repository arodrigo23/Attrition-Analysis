# Employee Attrition Analysis
Goal: Use Python and Tableau to analyze employee attrition at a company and formulate recommendations to increase employee retention.

\* The interactive dashboard pictured below can be found [here](https://public.tableau.com/views/EmployeeAttrition_17247825466550/Dashboard2?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link).

![dashboard-screenshot](https://github.com/user-attachments/assets/57c435df-eac8-43b7-88ee-47a8ac067ec8)

## Key Metrics
* Salary
* Number of hires and terminations each year
* Age group
* Reason for termination: voluntary vs involuntary
* Overtime: whether an employee had overtime

## Summary of Insights
* There is a noticeable gender pay gap across different job titles, with male employees generally earning more than female employees.
* Employees who had overtime are more likely to leave voluntarily within their first year. The exception to this was in 2020, which saw a relatively high number of employees doing overtime but a low number of employees leaving if they were hired in 2019 or 2020.
* The 35-45 age group has the highest number of voluntary terminations, indicating potential dissatisfaction or other factors among mid-career employees.
* There was a marked decrease in hiring during 2020, presumably due to the COVID-19 virus. The year 2020 also saw the highest number of involuntary terminations.
* The Operations, Sales, and IT departments had the highest number of voluntary terminations every year from 2015 to 2024.
* The total number of hires and terminations (both voluntary and involuntary) decreased in the last year.

## Recommendations
* Consider conducting an anonymous employee satisfaction survey aimed at identifying specific reasons for voluntary termination (e.g., total compensation, leadership quality, growth opportunities, work-life balance). 
* Conduct a detailed analysis of the gender pay gap, particularly in leadership roles where the disparity is most pronounced.
* Consider revising overtime policies or offering additional support to employees working overtime in their first year at the company in order to improve retention.
* Investigate why the 35-45 age group is experiencing the highest rate of voluntary terminations. This could involve conducting surveys or focus groups to identify specific issues and develop strategies to retain experienced employees.
* Focus on understanding the reasons behind the voluntary termination rates for the Operations, Sales, and IT departments, and research targeted retention strategies.

---

## Project Notes
* The dataset for this project was generated in Python using pandas, numpy, and faker libraries. (see Jupyter notebook in this repository for details).
