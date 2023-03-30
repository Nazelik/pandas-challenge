# pandas-challenge

## Analyzing School and Standardized Test Data
<br/><br/>
This project is about analyzing the school and test scores data of city's district. The goal of analysis is helping the school board and mayor make strategic decisions regarding future school budgets and priorities. There are given two csv files with an information of every student's math and reading scores, as well as various information on the schools they attend and about all the schools in the district.


The script does the following:
### District Summary

 
* Calculates the total number of unique schools
* Calculates the total number of students
* Calculates the total budget
* Calculates the average (mean) math score
* Calculates the average (mean) reading score
* Calculates the percentage of students who passed math
* Calculates the percentage of students who passed reading
* Calculates the percentage of students that passed both math and reading
* Creates a new DataFrame for the above calculations called district_summary

### School Summary
* Selects the school type
* Calculates the total student count
* Calculates the per capita spending
* Calculates the average test scores
* Calculates the number of schools with math scores of 70 or higher
* Calculates the number of schools with reading scores of 70 or higher
* Calculates the schools that passed both math and reading with scores      70 or higher
* Calculate the passing rates
* Creates a new DataFrame for the above calculations called per_school_summary


### Highest-Performing Schools by Percentage of Overall Passing
* Sorts the schools by % Overall Passing in descending order
* Saves the results to a DataFrame called top_schools
* Displays the first 5 rows

### Lowest-Performing Schools by Percentage of Overall Passing
* Sorts the schools by % Overall Passing in ascending order
* Saves the results to a DataFrame called bottom_schools
* Displays the first 5 rows

* ### Math Scores by Grade
* Separates the data by grade
* Groups by "school_name" and takes the mean of each
* Selects only the math_score
* Combines each of the scores above into single DataFrame called math_scores_by_grade

### Reading Scores by Grade
* Separates the data by grade
* Groups by "school_name" and takes the mean of each
* Selects only the reading_score
* Combines each of the scores above into single DataFrame called reading_scores_by_grade

### Scores by School Spending
* Bins the data by the spending ranges
* Calculates the averages
* Creates the spending_summary DataFrame using the binned and averaged spending data

### School SummaryScores by School Size
* Bins the data by the school sizes
* Calculates the averages
* Creates the size_summary DataFrame using the binned and averaged size data 

### Scores by School Type
* Groups the per_school_summary DataFrame by "School Type" and average the results
* Selects the new column data
* Creates a new DataFrame called type_summary that uses the new column data 

### Written Report
The written report presents a cohesive written analysis that:

* Summarizes the analysis

*  Draws correct conclusions and comparisons from the calculations 
  
<br/><br/><br/>

### Directory tree
. PyCitySchools ---> PyCitySchools_Final.ipynb, Resources( ---> schools_complete.csv, students_complete.csv)


## References
This project is a part of UC Berkeley "Data Analysis and Visualisation" Boot Camp education services.


In projects' descriptions, some paragraphs are copy/pasted from 'Module 4 Challenge' of UC Berkeley Data Analytics and Visualisation Bootcamp course.
PyCitySchools_starter file is used as a tamplate.

Script author - Nazeli Mnatsakanyan
 
Mar-27-2023
