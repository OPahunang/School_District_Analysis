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
   The modification of Thomas High School 9th grade with grade to Nan did not have much of a big impact this is due to the numbers of 9th graders student which is 461.
 
 District Summary Initial Analysis
 ![district_summary_initial_analysis.png](https://github.com/OPahunang/School_District_Analysis/blob/main/Resources/district_summary_initial_analysis.png)
 
 District Summary Modified Analysis
 ![district_summary_after_update.png](https://github.com/OPahunang/School_District_Analysis/blob/main/Resources/district_summary_after_update.png)


## Summary:
