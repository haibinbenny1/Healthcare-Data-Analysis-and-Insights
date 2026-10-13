# Healthcare Data Analysis and Insights

## 1. Data Cleaning

- **Missing Values:** Counted missing values marked with `?` in both tables using Excel `COUNTIF`.
- **Month and Year:** Filled missing months with `Sep` and missing years with the rounded average year.
- **Categorical Values:** Used the most frequent values (mode) to fill missing `smoker`, `Hospital tier`, and `City tier` values.
- **State ID:** Replaced missing values with `Unknown`.

## 2. Data Transformation

- **Customer Names:** Split names into Title, First Name, and Last Name.
- **Major Surgeries:** Converted text values into numerical values.
- **Heart Issues and Smoker:** Checked and corrected inconsistent values.
- **Weight Status:** Categorized BMI into Underweight, Normal Weight, Overweight, and Obesity.
- **Diabetes Status:** Categorized HbA1C into Normal, Prediabetes, and Diabetes.
- **Date of Birth:** Combined year, month, and date into one column and applied the `DD-MMM-YYYY` format.
- **Age:** Calculated customer age as of 8 June 2023.
- **Charges:** Applied US dollar currency formatting ($).

## 3. Data Exploration, Analysis and Visualization

- **Data Integration:** Combined all three tables into a new `Healthcare` sheet using VLOOKUP and Customer ID.
- **Cancer History:** Compared cancer history among smokers and non-smokers using a pie/donut chart.
- **Transplant Analysis:** Compared total major surgeries and average HbA1C for patients with and without transplants.
- **Healthcare Charges:** Compared charges by Weight Status and Diabetes Status using bar/column charts.
- **Hospital Analysis:** Compared average charges by hospital tier across states.
- **Age and Health:** Explored relationships between age, BMI, and HbA1C using scatter plots.
- **Age and Charges:** Analyzed the relationship between age and healthcare charges.

## 4. Dashboard Creation

- **Interactive Dashboard:** Combined key insights and visualizations into one dashboard.
- **Charts:** Used pie/donut, bar/column, and line/scatter charts.
- **Slicers:** Added `Weight Status` and `Diabetes Status` slicers to filter the visualizations.

## Conclusion

This project uses Microsoft Excel to clean, transform, analyze, and visualize healthcare data to understand patient health profiles and healthcare costs.
