# Healthcare-Data-Analysis-and-Insights
1. Data Cleaning

Question 1: How many missing values are present in each column?

Description: Used Excel COUNTIF to count missing values marked with ? in the Medical Examinations and Hospitalization Details tables.

Explanation: The missing values were counted for each column using the formula =COUNTIF(range,"~?").

Question 2: How were missing month and year values handled?

Description: Replaced missing month values with Sep and missing year values with the average year rounded to the nearest integer.

Explanation: Used the specified month value and Excel's AVERAGE and ROUND functions to fill missing data.

Question 3: How were missing categorical values handled?

Description: Identified the most frequent values in the smoker, Hospital tier, and City tier columns.

Explanation: Used the mode of each column to replace missing values.

Question 4: How were missing State ID values handled?

Description: Checked the State ID column for missing values.

Explanation: Replaced missing values with Unknown when the correct state could not be identified.

2. Data Transformation

Question 1: How was the names column split?

Description: Split the names column into Title, First Name, and Last Name.

Explanation: Separated the full names into meaningful columns for easier analysis.

Question 2: How was NumberOfMajorSurgeries converted to numerical data?

Description: Replaced non-numeric text with meaningful numerical values.

Explanation: Converted surgery information into numbers so it could be used in calculations and analysis.

Question 3: How were inconsistencies in Heart Issues and smoker handled?

Description: Checked both columns for inconsistent values and formatting.

Explanation: Standardized values such as Yes and No to maintain consistency.

Question 4: How was Weight Status created?

Description: Created a new column named Weight Status using BMI values.

Explanation: Categorized BMI as follows:

Below 18.5: Underweight

18.5–24.9: Normal Weight

25.0–29.9: Overweight

30.0 and above: Obesity

Question 5: How was Diabetes Status created?

Description: Created a new column named Diabetes Status using HbA1C values.

Explanation: Categorized HbA1C as follows:

Below 5.7: Normal

5.7–6.4: Prediabetes

6.5 and above: Diabetes

Question 6: How were year, month, and date combined?

Description: Combined the year, month, and date columns into Date of Birth.

Explanation: Formatted the resulting date using the custom format DD-MMM-YYYY.

Question 7: How was customer age calculated?

Description: Calculated customer age using the date of birth and the dataset collection date, 8 June 2023.

Explanation: Used the date difference to determine each customer's age.

Question 8: How was the charges column formatted?

Description: Formatted the charges column as currency in US dollars ($).

Explanation: Applied currency formatting to make healthcare costs easier to read.

3. Data Exploration, Analysis and Visualization

Question 1: How were the three tables combined?

Description: Created a new worksheet named Healthcare and combined the three tables using Customer ID and VLOOKUP.

Explanation: Retained the required columns to create a consolidated dataset for analysis.

Question 2: What is the distribution of cancer history among smokers and non-smokers?

Description: Compared cancer history between smokers and non-smokers using a pie or donut chart.

Explanation: Visualized the distribution of cancer history across smoking groups.

Question 3: How do surgeries and HbA1C differ by transplant history?

Description: Compared total major surgeries and average HbA1C between patients with and without a transplant history.

Explanation: Used summary tables and charts to compare both groups.

Question 4: How do healthcare charges vary by Weight Status and Diabetes Status?

Description: Compared healthcare charges across weight and diabetes categories using column or bar charts.

Explanation: Visualized differences in healthcare costs between the categories.

Question 5: How do average charges vary by hospital tier and state?

Description: Compared average healthcare charges for each hospital tier across different states.

Explanation: Used a chart to identify differences in average charges across hospital tiers and states.

Question 6: Is there a relationship between age, BMI, and HbA1C?

Description: Explored the relationships between age and BMI, and age and HbA1C using scatter plots.

Explanation: Examined whether these health measurements show any correlation with age.

Question 7: What is the relationship between age and healthcare charges?

Description: Analyzed age and healthcare charges using a scatter plot.

Explanation: Examined how healthcare costs vary across different ages.

4. Dashboard Creation

Question: How can healthcare insights be presented in an interactive dashboard?

Description: Created a dashboard combining the key charts and analysis results.

Explanation: Added pie/donut charts, column/bar charts, line/scatter plots, and slicers for Weight Status and Diabetes Status to filter the visualizations and compare results.

Conclusion

This project uses Microsoft Excel to clean and transform healthcare data, analyze patient health information and healthcare costs, and present key findings through charts and an interactive dashboard.
