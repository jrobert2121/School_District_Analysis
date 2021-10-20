# School District Analysis

## Project Overview

An analysis of a school district was completed and included a high level snapshot of the district's metrics, a per school overview of metrics, school performance based on budget per student, school size, and type of type.  In addition to the overall passing rate for the top 5 and bottom 5 schools, the average math and reading scores received by students in each grade at each school was analyzed.  However, the school board was notified of suspected academic dishonesty surrounding the ninth grade scores at Thomas High School.  Therefore, it was necessary to eliminate these scores and re-run the analysis.

## Purpose
Determine the effects on the school district when removing ninth grade scores from Thomas High School.

## Resources
- Data Sources: [students_complete.csv](Resources/students_complete.csv), [schools_complete.csv](Resources/schools_complete.csv)
- Software: Python 3.7.10, Jupyter Notebook 6.3.0

## Process
The analysis was completed using the pandas and numpy dependencies.  After an initial review of the data sources, it was determined that cleaning the data was in order to remove any prefixes or suffixes in the student name before proceeding further.  

## Results
use bulleted lists and images of DataFrames as support and address following questions

- The district summary was not severely impacted by the removal of ninth grade score's from Thomas High School. With the exception of the Average Reading Score, the other categories experienced nominal decreases.
 - Original District Summary
 ![Original District Summary](Resources/Original_district_summary_df.png)

 - Revised District Summary
 ![Revised District Summary](Resources/Revised_district_summary_df.png)

- The school summary was also not impacted tremendously by the changes made to Thomas High School.  Thomas High School remained the second highest performing high school when ranked by % Overall Passing.
 - Original School Summary ordered by descending % Overall Passing results (displaying top five schools)
 - ![Original Top School Summary](Resources/Original_top_school_summary.png)

 - Revised School Summary ordered by descending % Overall Passing results (displaying top five schools)
 - ![Revised Top School Summary](Resources/Revised_top_school_summary.png)

- How does replacing the ninth graders' math and reading scores affect THS performance relative to the other schools. When replacing the ninth grade math scores with NaN, the average math score for Thomas High School (THS) decreases from 83.42 to 83.35.  THS now falls in line with Griffin and Shelton High School's math scores, which were 83.35 and 83.36 respectively.  In regards to the Average Reading Score for THS, the score had a nominal increase from 83.8 to 83.9.  Interestingly, while the average reading score did increase, the % passing reading fell from 97.31% to 97.02%.  Yet, THS still has one of the highest average reading scores amongst the other schools.  Only 4 other schools had higher reading scores: Cabrera High School, Pena High School, Wilson High School and Wright High School.  


- In addition to revising the district and school summaries, the following was also reviewed for impact when removing ninth grade scores at Thomas High School:
 - Math and reading scores by grade were not impacted.  Ninth grade scores at Thomas High School reflected "Nan" but all other scores remained stable as seen in the below screenshots.
  - Original Math Scores by Grade vs. Revised Math Scores by Grade
  
  ![Original scores by grade](Resources/Original_scores_by_grade.png)    ![revised math scores by grade](Resources/revised_math_scores_by_grade.png)
 - scores by school spending
 - scores by school size
 - scores by school type

## Summary

Summarize 4 charges in the updated school district analysis after reading and math scores for the ninth grade at THS have been replaced with nans