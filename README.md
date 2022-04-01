# School District Analysis
## Overview Of The School District Analysis:

This analysis is aiming the find the most accurate results of the school scores by analyzing the math and reading scores from multiple aspects such as classification, size, and budget. However, due to some academic dishonesty, we had to process Thomas High School's 9th 
grade's result differently. The report below shows the steps of the updated School District Analysis.

## Results
### How is the district summary affected?
- Before removing the Thomas High School 9th Grades Math and Reading Scores
![image](https://user-images.githubusercontent.com/98247252/161177437-7d4739f8-39ce-45da-ac1e-a28e045bb905.png)


- After removing the Thomas High School 9th Grades Math and Reading Scores
![image](https://user-images.githubusercontent.com/98247252/161177571-f4790cb0-df1a-4593-8de9-df4bcda38f71.png)

According to 2 charts, after removing the 9th grades scores, the result is affected on average by 0,2%.

### How is the school summary affected?
- Before Removing the 9th Graders' scores
![image](https://user-images.githubusercontent.com/98247252/161178510-cbbeb63a-8a99-4207-9e0b-c5a5829ea429.png)

- After removing the Thomas High School 9th Grades Math and Reading Scores
![image](https://user-images.githubusercontent.com/98247252/161178779-b7ea3f4b-1e1d-4a10-8769-94b061929105.png)

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

According to the charts above, for Thomas High School, there are no significant changes in average math and reading grades, however, we can see significant changes in 
passing percentages for reading and math.

### How does replacing the ninth-grade scores affect the following:

#### Math and reading scores by grade:
In order the find the most accurate overall result, We dropped the Thomas High School's 9th graders reading, math, and other related scores.

#### Scores by school spending:
- Before Removing the 9th Graders' scores
![image](https://user-images.githubusercontent.com/98247252/161181155-4eddfb62-3dc5-4243-a304-bbcf029f84e3.png)

- After removing the Thomas High School 9th Grades Math and Reading Scores
![image](https://user-images.githubusercontent.com/98247252/161181211-c6986129-5ecd-4deb-83d5-0c289cc344ed.png)


We can see some differences in the $631 - $645 Spending range, This is an indicator that Thomas High School belongs to this scale and, in every column, we can observe a 0,04 % change on average.

#### Scores by school size:
- Before removing the Thomas High School 9th Grades Math and Reading Scores
![image](https://user-images.githubusercontent.com/98247252/161183023-88e5edfa-48e3-4afc-b19c-c81651c42954.png)


- After removing the Thomas High School 9th Grades Math and Reading Scores
![image](https://user-images.githubusercontent.com/98247252/161182939-db79d129-70ee-4d1b-84b8-69dae42d58da.png)

According to the minor changes on the two charts above, we can see that Thomas High School belongs to the Medium school size category.

#### Scores by school type:

- Before removing the Thomas High School 9th Grades Math and Reading Scores
![image](https://user-images.githubusercontent.com/98247252/161183615-63459578-6c99-42df-b2b3-d3fdac780b6b.png)


- After removing the Thomas High School 9th Grades Math and Reading Scores
![image](https://user-images.githubusercontent.com/98247252/161183558-6a7d3cc8-29cc-490a-ac55-053f74703911.png)

According to the differences in the two charts above, Thomas High School belongs to Charter Category.

## Summary:

To process the data for the schools and students, we used python's pandas library and jupyter environment. We cleaned the data and made it ready to read and split it into multiple categories. most of our work was trying to determine and understand relations between scores, budgets, populations of the schools, solving some dishonesty problems among 9th grades in Thomas High School. Grouped, filtered, and created new data frames to categorize our results.  

Overall, we replaced the 9th graders reading, math, and related scores with NaNs, and these changes did not affect the other results significantly. In general, the result differences between the before and after charts are less than 0.1. To improve the dishonesty results we need to seek many further ways.
