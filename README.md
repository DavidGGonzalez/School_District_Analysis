# School District Analysis

## Overview

Previous analysis was a success, but the **School Board** has notified Maria and her supervisor that the ` students_complete.csv ` file shows evidence of academic dishonesty involving the **9th graders** from the **Thomas Hight School**. After brainstorming about the approach to proof school board doubts about the data, we agreed on removing Thomas High School 9th graders math and reading scores and repeat the analysis would help us to verify the issue.

## Process

1. From the provided `csv` file remove the 9th graders math and reading scores by replacing them with a **NaN** (Not-a-Number) value.
2. Repeat the entire School Distric Analysis.
3. Write a report describing our findings.
4. Upload project on GitHub to results.

## Resources
* Data Source: `students_complete.csv` file.
* Language:
  - Python 3.9.7
* Libraries:
  - Pandas
  - Numpy
* Development tools: 
  - Jupyter Notebook 6.4.6
  - Visual Code 1.62.3; just to edit README.md file.


# Analysis

After removing **9th graders** Math and Reading scores from the sample, we found there were only **461** students representing about **0.00255%** of the total of **39,170** students population currently enrolled in high school for this school district, so, overall results ***should not*** be significanlty impacted, but let's review them one by one.

> Note: After removing **9th graders** from the students count, we got **38,709** that will be used in our final analysis. All pictures will be numbered so we can easily identify their source, where **1** will indicate initial analysis and **2** will be final analysis after removing 9th graders from the total count ans scores.

## School District Summary

![Distric Summary #1](/Resources/District_Summary_1.png)
![Distric Summary #2](/Resources/District_Summary_2.png)

As suspected, removing 461 records from the total would affect district results by a minimal margin as pictures below shows, were `Average Math Score` and `% Passing Math` dropped only about ***0.1*** and ***0.2%*** respectively, and a minimal impact to the `% Overall Passing` of about **0.3%**.


## School Summary
### How was the Thomas High School affected?

![School Summary Header](/Resources/School_Summary_Header.png)
![School Summary #1](/Resources/School_Summary_1.png)
![School Summary #2](/Resources/School_Summary_2.png)

The school summary does not show a significan impact to the `Average Math Score` and `Average Reading Score`, it does for the `% Passing Math`, `% Passing Reading`, and the `% Overall Passing` but only about the same percentage that represents the number of 9th grade students that were removed from the calculation (***28%***).

### Top 5

![Top 5 #1](/Resources/Top5_1.png)
![Top 5 #2](/Resources/Top5_2.png)

Despite the fact 9th graders were removed from the total population of students from the ***Thomas High School***, they keept their second place in the **Top 5** list for this School District. Notice that calculation were done using the new calculated total students count were ***9th graders*** were removed.

## Scores by School Spending Summary

![Spending per Student #1](/Resources/SpendingPerStudent_1.png)
![Spending per Student #2](/Resources/SpendingPerStudent_2.png)

Results above show that removing the ***Thomas High School 9th graders math and reading grades*** from the data set did not affect averages and percentages within the `$630-644` spending per student bin.

## Scores by School Size Summary

![School Size #1](/Resources/SchoolSize_1.png)
![School Size #2](/Resources/SchoolSize_2.png)

Results above show that removing the ***Thomas High School 9th graders students (461)*** from the data set did not affect total numbers by School Size, Thomas High School continue to be within the `Medium (1000-2000)` bin with 1,174 students.

## Scores by School Type

![School Type #1](/Resources/SchoolType_1.png)
![School Type #2](/Resources/SchoolType_2.png)

Results above show that removing the ***Thomas High School 9th graders students (461)*** from the data set did not affect total numbers by School Type (`Charter`).

# Results
By removing the ***Thomas High School 9th graders students (461)*** from the dataset did not affect previous reported results at the district level, but individually for this high school. The fact that ***Thomas High School*** and ***District*** average math and reading scores were not affected by removing 461 9th grade students, clearly indicate _there is no evidence_ of **acedemic dishonesty**.



















