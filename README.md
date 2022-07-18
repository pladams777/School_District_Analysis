# School District Analysis
## Overview of Project
The purpose of this project was to assist a school district data analyst in analyzing data on student funding and student standardized test scores. This analysis will assist the school board in their decisions about the school budgets and priorities. After the analysis was complete it was discovered that there was evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appeared to have been altered. It was then necessary to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact; and then to repeat the school district analysis with the updated data.

## Results

* The school district summary was not significantly affected by removing the suspect scores and the rankings remained the same.
*	The school summary for Thomas High School was significantly worse when the 9th grade scores were changed removed.
*	Adjusting the code to only read the 10th  through 12th grade scores for Thomas HS Improved their performance.
### Thomas HS with ninth grade scores removed:
![THS1](https://user-images.githubusercontent.com/107540080/179455558-8b7245df-ee43-4bb5-b7c6-f350bceac971.PNG)

### THomas HS recalculated for 10th - 12th only:
![THS2](https://user-images.githubusercontent.com/107540080/179455631-f9fa73ab-e1e1-4445-87b8-c44ba37e6369.PNG)

## Summary
There were significant changes when voiding the ninth grade scores in both reading and math for Thomas HS and the school fell out of the top 5 schools in the district. Excluding them from the school count brought the scores back to a similar range and the school back to its top five placement. 
