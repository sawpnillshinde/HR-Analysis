# HR-Analysis
EDA of HR Data using python
Conclusion:
# Constant Values: ‘EmployeeCount’, ‘Over18’, and ‘StandardHours’ have constant values, which means they might not provide useful information for a model.
# High Correlations: ‘Age’ and ‘TotalWorkingYears’, ‘MonthlyIncome’ and ‘TotalWorkingYears’, ‘MonthlyIncome’ and ‘JobLevel’, ‘PercentSalaryHike’ and ‘PerformanceRating’ show high correlations. This could indicate redundancy in your data.
# Work Experience: ‘TotalWorkingYears’ is highly correlated with ‘Age’, ‘MonthlyIncome’, ‘YearsAtCompany’, and ‘JobLevel’. This suggests that as employees get older and spend more time at the company, they tend to have higher incomes and job levels.
# Company Loyalty: ‘YearsAtCompany’, ‘YearsInCurrentRole’, ‘YearsSinceLastPromotion’, and ‘YearsWithCurrManager’ are all highly correlated. This could indicate that employees who stay at the company longer tend to stay in their roles longer, get promoted, and work with the same manager.
# Department and Job Role: ‘Department’ is highly correlated with ‘EducationField’ and ‘JobRole’, and ‘JobRole’ is also highly correlated with ‘JobLevel’. This could suggest that certain departments require specific education fields and have specific job roles and levels.
# Marital Status and Stock Options: ‘MaritalStatus’ is highly correlated with ‘StockOptionLevel’. This could indicate that marital status might influence the level of stock options.
# Zeros in Data: Several fields like ‘NumCompaniesWorked’, ‘TrainingTimesLastYear’, ‘YearsAtCompany’, ‘YearsInCurrentRole’, ‘YearsSinceLastPromotion’, and ‘YearsWithCurrManager’ have a significant number of zeros. This could indicate a lack of experience or newness in the role or company.
# Performance Rating: ‘PerformanceRating’ is highly correlated with ‘PercentSalaryHike’, indicating that employees with higher performance ratings might receive higher salary hikes.
# Job Level: ‘JobLevel’ is highly correlated with ‘MonthlyIncome’ and ‘TotalWorkingYear’, suggesting that higher job levels are associated with higher income and more years of work experience.
​
