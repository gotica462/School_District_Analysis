# School_District_Analysis

## Overview of the School District Analysis

The school board has found evidence of academic dishonesty in the reading and math scores of Thomas High School students, especifically those in the 9th grade. The purpose of this analyisis is to a new school distric analyisis of the scores replacing those scores afected with NAN, and see how those replacements affect the overal analysis of the school. 
      
## Results 

To get the new results we first had to replace all the scores of the 9th graders with NaN. To do this we used the loc() function in pandas. See link
https://github.com/gotica462/School_District_Analysis/blob/main/PyCitySchools_Challenge.ipynb


### District Summary

After doing the analysis we can the that were 471 scores affected by this measure, and now we can proceed to to the school district analyisis.

See images below:

Before replacing the scores

![image](https://github.com/gotica462/School_District_Analysis/blob/main/Counting%209th%20Grade%20in%20Thomas%20High.png)

After replacing the scores

![image](https://github.com/gotica462/School_District_Analysis/blob/main/Not%20Counting%209th%20Grade%20in%20Thomas%20High.png)


From this analysis we can determine:
- Avg. Math Score went down .1 point
- Avg. Reading Score stayed the same.
- The percentage of students who passed math when down .2% and the percentage of those passing reading went down .3%
- The overall passing percentage went down a .1%

### School Summary

Here are the results for the school summary.

Before replacing the scores

![image](https://github.com/gotica462/School_District_Analysis/blob/main/School%20summary%20counting%209th%20Grade.png)

After replacing the socores

![image](https://github.com/gotica462/School_District_Analysis/blob/main/School%20summary%20not%20counting%209th%20grade.png)

It is important to know that although it says the same number of students on both images, we did not change the total number of students affected, we only change the percentage and then replace it with the new percentage for only grades 10th to 12th. That's why the changes we see are minimal in the passing percentages and the average of the scores. If we had not replace the percentages for only 10th to 12th grade the passing percentage would decrease considerable but it would not gives un an accurate result.

As we can see replacing the scores of the 9th grades had a minimal effect in Thomas High standings, as they still are in the top 5 of schools in terms of performance

![image](https://github.com/gotica462/School_District_Analysis/blob/main/Top%205%20schools.png)

#### Math Scores by Grade

![image](https://github.com/gotica462/School_District_Analysis/blob/main/Math%20Scores%20by%20Grade.png)

#### Reading Socres by Grade 

![image](https://github.com/gotica462/School_District_Analysis/blob/main/Reading%20Scores%20by%20Grade.png)

Since we replace the scores of the 9th Grade with nan, the scores are not affected at all.

#### Scores by School Spending

![image](https://github.com/gotica462/School_District_Analysis/blob/main/Scores%20by%20School%20Spending.png)


#### Scores by School Size

![image](https://github.com/gotica462/School_District_Analysis/blob/main/Scores%20by%20School%20Size.png)

#### Scores by School Type

![image](https://github.com/gotica462/School_District_Analysis/blob/main/Scores%20by%20School%20Type.png)

## Summary











