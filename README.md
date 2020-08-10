# School District Grade Analysis

## Overview

The purpose of this project is to analyze the math and reading scores of various schools in the school district to gain insights. However based on the initial analysis, it was determined that the scores for Thomas High School, 9th grade results showed academic dishonesty. To upload state testing standards additional analysis was perfomed by replacing the reading and math scores of Thomas High School, 9th grade students with "NaN"(0). A comparison of before and after results are provided below.

## Results

Various metrics were used for analysing the school district data. The results based on the analysis for these metrics are provided below.

### District Summary Impact

As seen in the befor and after images below,

- The average math score has reduced by .2%
- The average english score remains unchanges
- The % of students passing math has gone down by 1%
- The % of students passing english has gone down by 1%
- The % of students passing both math and eglish has gone down by 1%

![district_Summary_b](https://github.com/ssathyanath/School_District_Analysis/blob/master/Images/District_Summary_Before.PNG)

![district_summary_A](https://github.com/ssathyanath/School_District_Analysis/blob/master/Images/District_Summary_After.PNG)

### School Summary Impact

Since the update was only to the Thomas High School, the school summary for all the other schools has not been impacted. The only impact is to Thomas High School, which is discussed in the next section

### Impact on Thomas High School’s performance

When looking at the metrics after the change, the Average math and reading scores are impacted minimally (<1%). However the % of students passing math, % of students passing english and % of students passing both has significantly reduced (~30%). This has pushed Thomas high school lower down the list of the top school by performance

![Thomas_High_School](https://github.com/ssathyanath/School_District_Analysis/blob/master/Images/Thomas_high_school_summary.png)

### Impact to Other Metrics

- Math and reading scores by grade: The change was to replace only the scores of 9th grade students in Thomas high school, there are no impacts to scores by grades for other grades or schools. The only impact is to the 9th grade score for Thomas High School, which shows as NaN.

- Scores by school spending: Thomas High school is in "$630 - 644" spending range. The % pasing Math, % Passing Reading and % Overall Passing have all reduced as seen in the below image. There is no impact to the other spending categories.

![Spending_Score](https://github.com/ssathyanath/School_District_Analysis/blob/master/Images/Spending_Range_Summary.png)

- Scores by school size: Thomas High school is in "Medium" school range. The % pasing Math, % Passing Reading and % Overall Passing have all reduced as seen in the below image. There is no impact to the small and large school categories.

![schoolsize_Score](https://github.com/ssathyanath/School_District_Analysis/blob/master/Images/Size_Summary.png)

- Scores by school type: Thomas High school is a "Charter" school. As with other metrics the % pasing Math, % Passing Reading and % Overall Passing have all reduced. There is no impact to the "District" school type.

![schooltype_Score](https://github.com/ssathyanath/School_District_Analysis/blob/master/Images/School_Type_Summary.png)

Summary:
There are various insights we can gain from the above analysis. To summarize, below are the four major changes.

- The average math and reading scores at the district level remain mostly unchanged. The % of students passing in math, reading and overall groups have come down by 1%
- There are no impacts to other school summary. The major impacts are to Thomas High school % pasing Math, % Passing Reading and % Overall Passing
- When comparing the scores by different categories, such as spending per student, school size and type, impacts are seem only to the category Thomas High school falls in. All other catgories remain unchanged
- There is no chage to scores by grade except for Thomas High school, 9th grade results, which shows up as Nan.

