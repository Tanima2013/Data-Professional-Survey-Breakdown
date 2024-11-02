# Data Professional Survey Breakdown
<h3>Introduction</h3>
This report presents findings from a survey of 630 data professionals, with insights into demographics, job satisfaction, salary distribution, and entry challenges within the data industry. The analysis addresses key questions regarding participant demographics, average salaries across professions, preferred programming languages, the ease of entering the field, and overall job and salary satisfaction.

<h3>Data Cleaning and Preparation</h3>
To ensure accurate analysis and insights, the data was first cleaned and transformed using Power Query. The following steps were taken to make the data usable for this report:

<h4>1. Removal of Empty Columns:</h4>
Columns with empty values were identified and removed to streamline the dataset and focus on relevant data points.

<h4>2. Calculating Average Salary from Ranges:</h4>
Some entries had salary information represented as ranges (e.g., "$50,000 - $60,000"). To standardize this, the average salary was calculated for each range, and a new column titled "Average Salary" was created to store these values. This enabled a more precise analysis of salary trends across professions.

<h4>Standardizing "Other" Values in Categorical Columns:</h4>
Certain columns contained various entries labeled with different variations of "Other" (e.g., "Others," "Other options"). These entries were standardized by consolidating them into a single "Other" category. This was achieved using the split column function, allowing for a clearer and more organized representation of categorical data.
These data cleaning steps ensured consistency and accuracy in the dataset, providing a solid foundation for further analysis and insights.

![Alt text](Dashboard.JPG)
