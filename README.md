# School_District_Analysis

## Overview of the School District Analysis
The purpose of this analysis was to use our skills with pandas and numpy to perform data operations on a dataset containing information about schools and metrics covering the students' performance in math and reading along with the budgets of the schools. This exercise involved a data clean-up operation to reflect the accurate analysis of the performance of the students in the schools. The main focus of the data correction involved modifying the dataset for the 9th graders from Thomas High School.

## Results

### How is the district summary affected?

![Original District Summary](https://github.com/dkatragadda/School_District_Analysis/blob/main/Resources/Original_District_Summary.png)

![Updated District Summary](https://github.com/dkatragadda/School_District_Analysis/blob/main/Resources/Updated_District_Summary.png)

As we can see from the results, modifying the data for the 9th graders in Thomas High School does not impact the district summary in a major manner. Some of the metrics are slightly modified such as the average math score, % passing math, % passing reading, and overall passing % have increased by 0.1%.

### How is the school summary affected?

![Original School Summary](https://github.com/dkatragadda/School_District_Analysis/blob/main/Resources/Original_School_Summary.png)

![Updated School Summary](https://github.com/dkatragadda/School_District_Analysis/blob/main/Resources/Updated_School_Summary.png)

The metrics for the school summary indicate that while all the metrics for Thomas High School related to the score have gone down, the only metric that has marginally improved is the average reading score which has gone up by 0.05. 

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

![Original Top 5 Schools](https://github.com/dkatragadda/School_District_Analysis/blob/main/Resources/Original_Top5_Schools.png)

![Updated Top 5 Schools](https://github.com/dkatragadda/School_District_Analysis/blob/main/Resources/Updated_Top5_Schools.png)

Replacing the scores for the 9th graders at Thomas High School did not impact the performance relative to other schools as it continued to be the second best school in terms of the overall passing %. 

### How does replacing the ninth-grade scores affect the following?

#### Math and reading scores by grade

As we can see from the above screenshots, the average math score reduced from 83.41 to 83.35 for Thomas High School and the average reading score went up to 83.89 from 83.84.

#### Scores by school spending

![Original Scores by School Spending](https://github.com/dkatragadda/School_District_Analysis/blob/main/Resources/Original_Score_by_School_Spending.png)

![Updated Scores by School Spending](https://github.com/dkatragadda/School_District_Analysis/blob/main/Resources/Updated_Score_by_School_Spending.png)

No changes in scores by school spending per student.

#### Scores by school size

![Original Scores by School Size](https://github.com/dkatragadda/School_District_Analysis/blob/main/Resources/Original_Score_by_School_Size.png)

![Updated Scores by School Size](https://github.com/dkatragadda/School_District_Analysis/blob/main/Resources/Updated_Score_by_School_Size.png)

No changes in scores by school size.

#### Scores by school type

![Original Scores by School Type](https://github.com/dkatragadda/School_District_Analysis/blob/main/Resources/Original_Score_by_School_Type.png)

![Updated Scores by School Type](https://github.com/dkatragadda/School_District_Analysis/blob/main/Resources/Updated_Score_by_School_Type.png)

No changes in score by school type.

## Summary

The four major changes in the updated school district analysis after the reading and math scores for the 9th graders at Thomas High School were replaced with NaNs are:
1. The change in the total number of students at Thomas High School as the count for the total number of students at Thomas High School was updated to 1174. 
2. The average math score changed to 83.35
3. The average reading score changed to 83.89
4. The overall % passing for Thomas High School changed from 90.94 to 90.63.
