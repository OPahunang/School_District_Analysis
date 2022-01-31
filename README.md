# School_District_Analysis

## Overview of the school district analysis:

City School District need the standardized state-test data for analysis, report and presentation to provide insight about performance trends and patters on school and district level. The data comes from variety of sources and variety of formats, the task is to aggregate and showcase the data to assist School Board and Superintendent in making decision on school budget and priorities.   

  Here is the list of deliverables for the analysis of the school district: 
  
    •	A high-level snapshot of the district's key metrics, presented in a table format
    •	An overview of the key metrics for each school, presented in a table format
    •	Tables presenting each of the following metrics:
      o	Top 5 and bottom 5 performing schools, based on the overall passing rate
      o	The average math score received by students in each grade level at each school
      o	The average reading score received by students in each grade level at each school
      o	School performance based on the budget per student
      o	School performance based on the school size 
      o	School performance based on the type of school
    
After the preparation of the data analysis, the school board had been notified of academic dishonesty, specifically reading and math grades for Thomas High School 9th graders.  The additional task is to replace the grades of Thomas High School of 9th graders to NaN for math and reading will keeping the rest of the data intact. This will repeat the school district analysis that was done and write a report to determine how these changes affected the overall analysis.

## Results:

### A. Deliverable 1: Requirements

Student_data before update

![student_data_before_THS_9th_reading_math_to_NaN_update.png](https://github.com/OPahunang/School_District_Analysis/blob/main/Resources/student_data_before_THS_9th_reading_math_to_NaN_update.png)

Script loc method script used

![ths_loc.png](https://github.com/OPahunang/School_District_Analysis/blob/main/Resources/ths_loc.png)

Student_data after running the script

![student_data_after_THS_9th_reading_math_to_NaN_update.png](https://github.com/OPahunang/School_District_Analysis/blob/main/Resources/student_data_after_THS_9th_reading_math_to_NaN_update.png)

### B. Deliverable 2: Repeat the Schol District Analysis


Script for Total Student and Total Student less THS 9th grade 

![student_count_and_student_count_less_ths_9th.png](https://github.com/OPahunang/School_District_Analysis/blob/main/Resources/student_count_and_student_count_less_ths_9th.png)


Script calculate the math and reading passing percentages

![calculate_math_reading.png](https://github.com/OPahunang/School_District_Analysis/blob/main/Resources/calculate_math_reading.png)


Script calculate the overall passing percentage

![calculate_overall_passing_percentage.png](https://github.com/OPahunang/School_District_Analysis/blob/main/Resources/calculate_overall_passing_percentage.png)


District Summary

![district_summary_after_update.png](https://github.com/OPahunang/School_District_Analysis/blob/main/Resources/district_summary_after_update.png)




1) How is the district summary affected?
   
   The modification of Thomas High School 9th grader grades to Nan did not have much of a big impact to District Summary analysis this is due to the numbers of 9th graders student which is only 461.
 
 District Summary Initial Analysis
 ![district_summary_initial_analysis.png](https://github.com/OPahunang/School_District_Analysis/blob/main/Resources/district_summary_initial_analysis.png)
 
 District Summary Modified Analysis
 ![district_summary_after_update.png](https://github.com/OPahunang/School_District_Analysis/blob/main/Resources/district_summary_after_update.png)

2) How is the school summary affected?

   The mofication did have a big impact on %Overall Passing, Thomas High School is still in top 2. 
   
   Initial Analysis
   ![top_5_schools.png](https://github.com/OPahunang/School_District_Analysis/blob/main/Resources/top_5_schools.png)
   
   Updated Anbalysis
   ![top_5_schools_after_update.png](https://github.com/OPahunang/School_District_Analysis/blob/main/Resources/top_5_schools_after_update.png)
   
3) How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

   When updated the 9th grader's scores math and reading, it did not affect other schools performance
   
   Initial Analysis by Grade - Math
   
   ![math_scores_by_grade_initial.png](https://github.com/OPahunang/School_District_Analysis/blob/main/Resources/math_scores_by_grade_initial.png)
   
   Updated Analysis by Grade - Math
   
   ![math_scores_by_grade_after_update.png](https://github.com/OPahunang/School_District_Analysis/blob/main/Resources/math_scores_by_grade_after_update.png)
   
   Initial Analysis by Grade - Reading 
   
   ![reading_scores_by_grade_initial.png](https://github.com/OPahunang/School_District_Analysis/blob/main/Resources/reading_scores_by_grade_initial.png)
   
   Updated Analysis by Grade - Reading
   
   ![reading_scores_by_grade_after_update.png](https://github.com/OPahunang/School_District_Analysis/blob/main/Resources/reading_scores_by_grade_after_update.png)
   
 4) How does replacing the ninth-grade scores affect the following:
    -Math and reading scores by grade
     There is a change on the figures
    
    -Scores by school spending 
     No change scores by school spending
     
    -Scores by school size
     No chnage on spending ranges(per student). Thomas High School $630-644, School Size Medium (1000 - 2000)
     
    - Scores by School type 
     No change on School Type for Thomas High School - Charter 
     
   
## Summary:

Analysis according to data

  - The more students in the school the lesser percentage of overall passing. 
  - Bigger per student budget is not a guarantee of high percentage of overall passing, in fact schools lesser per student budget is in the top 5 schools. 
  - Top 5 schools are all Charter school type and botton 5 schools are all District school type
  - School size medium (1000 -2000) and small (<1000) have higher percentage of overall passing.
