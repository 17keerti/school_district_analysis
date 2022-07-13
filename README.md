# School_district_analysis

## Overview of the school district analysis

In this module we helped Maria, analyze data on student funding and student standerdised test scores. With given data, we aggregated the data and showcased trends in school performance. This analysis will help school board and suprintendent in making decisions reagrding school budgets and priorities.
But, later school board notified Maria and her supervisor that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. So, we helped Maria to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact and repeated the school district analysis.

## Results

### **Impact on District Analysis**

Original Data
![District Original](resources/District%20Original.png)

Updated Data
![District Updated](resources/District%20Updated.png)

- The change of adding NaNs to all grade 9 Thomas High School math and reading scores did not have a large impact on the district analysis, with each metric decreasing by less that 0.5 percentage point each. Since there are only 461 students in grade 9 THS, removing their score doesn't impach the average so much.

### **Impact on School summary & Thoms High School Performance**

Original Data
![School Summary Original](resources/School%20Summary%20Original.png)

Updated Data
![School Summary Updated](resources/School%20Summary%20Updated.png)

- Thomas High School was not affected in the ranking by the update. It remained on 2nd position even after update. While the average math, reading and overall scores at Thomas High School were impacted by the update, the changes were not enough to change its relative ranking versus other schools.

### **Impact on Math and reading scores by grade**

Original Data (Math)

![Original Math Score](resources/original%20math.png)

Updated Data (Math)

![Updated Math Score](resources/update%20math.png)

Original Data (Reading)

![Original Reading Score](resources/original%20reading.png)

Updated Data (Reading)

![Updated Reading Score](resources/update%20reading.png)

- As we can see above, tables shows "NaN" for ninth grade at Thomas High School whereas the remaining data remained intact. Replacing 9th grade THS with NaNs doesn't affect other data.

### **Impact on Scores by school spending**

Original Data
![Spending Summary Original](resources/spending%20original.png))

Updated Data
![Spending Summary Updated](resources/spending%20updated.png)

- There was a slight change in the scores by school spending groups scores where Thomas High School is grouped, however the change is small with change of less than 0.1%. It is found that Average Scores and Passing Percentages do not increase as spending per student increases.

### **Impact on Scores by school size**

Original Data
![School size Summary Original](resources/size%20original.png)

Updated Data
![School size Summary Updated](resources/size%20updated.png)

- The scores for the Medium (1000-2000) size schools changed slightly which is less than 0.1%, this group was impacted as Thomas High School lies in this group. When considering School Sizes, "Large" Schools (Over 2,000 Students) have the lowest average scores and passing percentages

### **Impact on Scores by school type**

Original Data
![School size Original](resources/school%20type%20original.png)

Updated Data
![School size Updated](resources/school%20type%20updated.png)

- Thomas High School is a Charter type school, there is change but less than of 0.1% and no other school scores were affected.
  Overall, Charter schools generally performed better than District schools in this analysis.

## Summary

- Math and reading scores by grade - As we can see above, tables shows "NaN" for ninth grade at Thomas High School whereas the remaining data remained intact. Replacing 9th grade THS with NaNs doesn't affect other data.
- Scores by school spending - There was a slight change in the scores by school spending groups scores where Thomas High School is grouped.
- Scores by School Size - The scores for the Medium (1000-2000) size schools changed slightly
- Scores by School Type - There is change in Charter type grouping but by less than 0.1%.
