# Python

# Week 7 Python and Data Tasks

This repository contains my **Week 7 competency assessment** tasks for the **SQA Accredited HN Unit in Python and Data at Level 8**.

## Overview

This week’s work focused on using Python for:

- loading and validating CSV data
- cleaning and preparing datasets
- applying **recursion** for analysis
- applying **Fibonacci modelling** for simple prediction
- creating visualisations
- summarising findings in a short report

The main dataset used was:

- `TaySewage.csv`

## Tasks Completed

### 1. Load and Validate Data
A `load_data()` function was created to:

- read the CSV file
- inspect column names
- check for missing values
- detect duplicate rows
- preview the dataset structure

### 2. Clean Data
The data cleaning stage included:

- removing duplicate rows
- standardising river and city names
- converting pollution and year columns into numeric format
- removing rows with missing key values

### 3. Recursive Analysis
A recursive function was implemented to calculate average pollution levels for each river.

This function:
- processed records one by one
- added pollution values for the selected river
- counted matching entries
- returned the average at the end of the dataset

### 4. Fibonacci Trend Modelling
A Fibonacci function was used to generate a simple growth factor.

This was applied to:
- create a predicted contaminant index
- model simple future contamination trends for each city

### 5. Visualisation of Insights
Three visualisations were created:

- **Bar chart** showing average sewage levels by river
- **Line chart** showing predicted contaminant trends by city
- **Histogram** showing the distribution of pollution levels

### 6. Analysis and Reporting
The outputs helped identify:

- rivers with the highest contamination levels
- cities with rising sewage contamination
- possible unusual increases in contaminant indices

## Key Finding

The analysis showed that **Ericht** had the highest average pollution level, with an average of **36.80**.

## Files in This Repository

Typical files included in this project:

- `week7_submission.py`
- `cleanedTaySewage.csv`
- `average_pollution_by_river.csv`
- `future_contamination_predictions.csv`
- `average_pollution_by_river.jpg`
- `predicted_contaminant_trends_by_city.jpg`
- `pollution_distribution.jpg`
- `week7_report_summary.txt`

## Skills Demonstrated

Through this task, I practised:

- Python functions
- recursion
- Fibonacci logic
- CSV data handling with pandas
- data cleaning
- data visualisation using matplotlib
- reporting and interpretation of findings

## Reflection

This task helped me improve my confidence in Python by showing how coding concepts such as recursion and Fibonacci sequences can be applied to real datasets. It also strengthened my understanding of data cleaning, validation, and visual presentation of insights.

## Author

Created as part of my weekly competency assessment in Python and Data.
