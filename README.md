# School District Analysis

## Project Overview

An analysis of a school district was completed and included a high level snapshot of the district's metrics, a per school overview of metrics, school performance based on budget per student, school size, and type of type.  In addition to the overall passing rate for the top 5 and bottom 5 schools, the average math and reading scores received by students in each grade at each school was analyzed.  However, the school board was notified of suspected academic dishonesty surrounding the ninth grade scores at Thomas High School.  Therefore, it was necessary to eliminate these scores and re-run the analysis.

## Purpose
Determine the effects on the school district when removing ninth grade scores from Thomas High School.

## Resources
Data Sources: [students_complete.csv](Resources/students_complete.csv), [schools_complete.csv](Resources/schools_complete.csv)
Software: Python 3.7.10, Jupyter Notebook 6.3.0

## Process
The analysis was completed using the pandas and numpy dependencies.  After an initial review of the data sources, it was determined that cleaning the data was in order to remove any prefixes or suffixes in the student name before proceeding further.  

## Results
use bulleted lists and images of DataFrames as support and address following questions

- The district summary was not severely impacted by the removal of ninth grade score's from Thomas High School. With the exception of the Average Reading Score, the other categories experienced nominal decreases.
 - Original District Summary
 ![Original District Summary](Resources/Original_district_summary_df.png)

 - Revised District Summary
 ![Revised District Summary](Resources/Revised_district_summary_df.png)


- How is the school summary affected?
- How does replacing the ninth graders' math and reading scores affect THS performance relative to the other schools
- How does replacing the ninth grade scores affect the following:
 - Math and reading scores by grade
 - scores by school spending
 - scores by school size
 - scores by school type

## Summary

Summarize 4 charges in the updated school district analysis after reading and math scores for the ninth grade at THS have been replaced with nans