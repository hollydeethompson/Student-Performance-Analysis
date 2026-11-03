# Student Performance Analysis: Study Time, Absences, and Final Math Grades
## Executive Summary

This project analyzes mathematics performance data from 395 students using Google Sheets. The goal was to explore relationships between weekly study time, school absences, and final mathematics grades.

Using descriptive statistics, correlation analysis, and data visualizations, I identified patterns in student performance and investigated unusual values in the dataset.

Key findings include:
- Students reporting 5–10 hours of weekly study time had the highest average final grade (11.40 out of 20).
- School absences showed almost no linear correlation with final grades (r = 0.034).
- Approximately 9.6% of students received a final grade of zero, highlighting the importance of investigating unusual values and documenting data limitations.

This project demonstrates my ability to analyze data, identify patterns, create visualizations, and communicate findings clearly.
 

## Project Overview
This beginner data analytics project explores the relationship between students' weekly study time, school absences, and final mathematics course grades.

The analysis uses the Student Performance dataset from the UCI Machine Learning Repository. Google Sheets was used to organize, analyze, and visualize the data.

## Research Questions
1. Is weekly study time associated with students' final mathematics grades?
2. Is there a relationship between school absences and final mathematics grades?
3. What do the overall grade distributions tell us about student performance?

## Tools Used
- Google Sheets
- Formulas and descriptive statistics
- Charts and data visualization

## Key Findings

### Study Time and Final Grades
Average final grades generally increased across the weekly study-time categories. Students in the 5–10 hour category had the highest average grade (11.40 out of 20).

### Absences and Final Grades
The correlation between absences and final grades was approximately 0.034. This indicates an extremely weak linear relationship in this dataset.

### Overall Grade Distribution
The average final grade was 10.4, the median was 11, and the standard deviation was 4.6.

### Students with a Final Grade of Zero
Thirty-eight students (approximately 9.6% of the dataset) had a final grade of zero. All 38 also had zero recorded absences. The dataset does not explain why these students received a zero, so no assumptions are made about the circumstances.

## Limitations
This analysis identifies patterns and associations, not cause-and-effect relationships. The dataset does not explain why some students received a final grade of zero. Results should therefore be interpreted with these limitations in mind.

## Conclusion
The analysis suggests a modest pattern between weekly study time and final mathematics grades, while recorded absences showed almost no linear correlation with final grades. The project also highlights the importance of examining unusual values and understanding the limitations of a dataset.

## Data Source
UCI Machine Learning Repository — Student Performance Dataset  
https://archive.ics.uci.edu/dataset/320/student+performance
## Data Visualizations

### Average Final Grade by Weekly Study Time

![Average Final Grade by Weekly Study Time](Average%20Final%20Grade%20by%20Weekly%20Study%20Time.png)
### Absences vs. Final Math Grade

![Absences vs. Final Math Grade](Absences%20vs.%20Final%20Math%20Grade.png)

The correlation between absences and final math grades was approximately 0.034, indicating almost no linear relationship in this dataset.

### Earlier Math Performance by Final Grade Group

![Earlier Math Performance by Final Grade Group](Earlier%20Math%20Performance%20by%20Final%20Grade%20Group.png)

Students who received a final course grade of zero had substantially lower average grades during earlier grading periods (G1 and G2) than students who received a final grade above zero.

The dataset does not explain why these students received a zero, so these results should not be interpreted as evidence of a specific cause.
## Data Cleaning and Methodology

The dataset contains 395 student records. The analysis was completed using Google Sheets.

### Data Preparation
- Reviewed the study time, absences, and mathematics grade variables.
- Verified that the dataset contained 395 student records.
- Identified 38 students with a final mathematics course grade (G3) of zero.
- Investigated these records by comparing their earlier-period grades (G1 and G2) and recorded absences.
- Retained all 395 records because the dataset does not provide sufficient information to justify removing the zero grades.

### Analysis Methods
- Calculated descriptive statistics, including mean, median, and standard deviation.
- Compared average final grades across four weekly study-time categories.
- Calculated the Pearson correlation coefficient between absences and final grades.
- Created charts to visualize grade patterns and relationships.
- Compared earlier-period grades for students with final grades of zero versus those with grades above zero.

### Data Limitations
The dataset does not explain why 38 students received a final grade of zero. All 38 had zero recorded absences, but this does not establish the reason for their final grades.

The findings describe associations and should not be interpreted as evidence of causation.
