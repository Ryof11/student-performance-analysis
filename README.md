# student-performance-analysis
Exploratory data analysis of student scores and attendance using Python.
# Student Performance Analysis

## Project Overview

This project explores student performance using Python, Pandas, NumPy, and Matplotlib. The goal is to analyze students' scores and attendance, identify patterns in the data, and explore the relationship between attendance and academic performance.

## Objectives

* Explore and understand the dataset.
* Clean missing values and remove duplicate records.
* Calculate descriptive statistics for scores and attendance.
* Visualize student performance using different chart types.
* Investigate the correlation between attendance and scores.
* Summarize findings and acknowledge the limitations of the analysis.

## Dataset

The dataset contains information about 5 student records and includes the following columns:

| Column       | Description                     |
| ------------ | ------------------------------- |
| `student`    | Student name                    |
| `score`      | Student's score                 |
| `attendance` | Student's attendance percentage |

**Note:** This is a small, illustrative dataset intended for learning and practicing data analysis techniques.

## Tools and Libraries

* **Python** — Core programming language
* **Pandas** — Data manipulation and cleaning
* **NumPy** — Numerical computing
* **Matplotlib** — Data visualization

## Data Cleaning

The following preprocessing steps were performed:

* Identified missing values in the `score` column.
* Replaced the missing score with the mean of the available scores.
* Removed duplicate rows using Pandas.
* Checked for remaining missing values and duplicate records.
* Reviewed data types and descriptive statistics to assess data quality.

After preprocessing, the dataset contained 5 records and 3 columns, with no remaining missing values or fully duplicated rows.

## Exploratory Data Analysis

The analysis included descriptive statistics and the following visualizations:

* **Bar Chart:** Compared individual student scores and attendance.
* **Scatter Plot:** Explored the relationship between attendance and scores.
* **Histogram:** Examined the distribution of student scores.
* **Box Plot:** Visualized the distribution of scores and checked for potential outliers.

## Key Findings

* The average student score was **79.76**.
* The average attendance rate was **84.4%**.
* Scores ranged from **63 to 95**.
* Attendance ranged from **70% to 99%**.
* The Pearson correlation coefficient between attendance and scores was approximately **0.931**, indicating a strong positive linear association within this dataset.
* The box plot did not identify any outliers under its default rule.

## Limitations

* The dataset contains only five student records, so the findings cannot be generalized to a larger student population.
* Replacing a missing score with the mean may affect the distribution and statistical relationships.
* Correlation does not establish causation.
* The analysis is exploratory and does not predict student performance.

## What I Learned

Through this project, I practiced:

* Data cleaning and preprocessing with Pandas.
* Using descriptive statistics to understand numerical data.
* Creating visualizations with Matplotlib.
* Calculating and interpreting correlation.
* Communicating analytical findings and recognizing data limitations.

## Future Improvements

* Work with a larger and more realistic dataset.
* Explore additional factors that may relate to academic performance.
* Compare different approaches to handling missing data.
* Develop a more comprehensive analysis and communicate findings through a dashboard.

## Author

Created as a hands-on Python data analysis project to strengthen practical skills in data analysis and visualization.
