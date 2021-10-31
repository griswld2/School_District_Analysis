# School_District_Analysis

## Overview
The purpose of the analysis was to determine how school size, budgets, and types impacted overall student learning and passing percentages. In addition to analyzing how schools performed based off of those three criterias, the analysis also focused on what the impact would be on removing data on the disqualified students from Thomas High School. 

## Results
The impact of removing the disqualified Freshman students from Thomas High School had very minimal impact on the overall results of this analysis. It is more probable than not, that the overall impact is statistically insignifcant and within the standard margin of error when making inferences based off the sample schools in this analysis.

Small and Medium size schools tended to have a higher passing percentage and average math and reading scores than larger schools. Since the average is looking at a mean, it is possible that outliers could impact the results. 

School type (Charter vs District) had one of the most significant impacts on student education. Charter Schools had a 36% higher overall pass rate than district schools. Moreover, students in Charter school's had a significant advantage in passing math than students in District Schools. It is possible

One of the most interesting findings in the results is that schools with smaller spending ranges per student tended to do better than schools with larger spending ranges per students. Further analysis would have to be done to determine what the cause of this is.

![School_Size.PNG](https://github.com/griswld2/School_District_Analysis/blob/main/Resources/School_Size.PNG)


![School_Type.PNG](https://github.com/griswld2/School_District_Analysis/blob/main/Resources/School_Type.PNG)


![Spending_Ranges_Per_Student.PNG](https://github.com/griswld2/School_District_Analysis/blob/main/Resources/Spending_Ranges_Per_Student.PNG)



![Thomas_High_School.PNG](https://github.com/griswld2/School_District_Analysis/blob/main/Resources/Thomas_High_School.PNG)

The impact of removing the 9th grade student scores had very little impact to the Thomas High School Data. Since we simply removed their scores, it's possible that the averages and passing percentages are very similar across grades at Thomas High School. The data would have impacted much more if we would have included them as a zero.

Thomas High School Data:
* Thomas High School is a charter school that performed in line with the other charter schools
* Thomas High School would be classified as a medium sized school (1,635 Total Students) and performed in line with other medium sized schools
* Thomas High School spent a large amount per student and out-performed other schools that spent that much per student.

## Summary
Future analysis of how a school's size, budget, and type impact student performance should look at other descriptive statistics as well. This could include looking at what the statistical mode looks like instead of just the mean. A mode might give you a more accurate view than looking at a mean. 

In addition to looking at additional descriptive statistics, it might make sense for future analysis to look at a multi-index data frame. A multi-index data frame would allow us to see how different types of schools at different sizes impacted results, so we could test out if Charter schools performed better due to having smaller enrollments or if there were other factors involved. 
