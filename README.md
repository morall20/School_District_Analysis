# School_District_Analysis

## Overview of the school district analysis:

I am tasked with analyzing the data offrom the City School District; in order complete this project I will perform different analysis including student reading and math scores, averaging there scores out by district, creating school summaries and performing budget analysis. Thers's also concern with academic dishonesty; specifically, reading and math grades for the Thomas High School (THS) ninth graders that appear to have been altered. The school board is unaware of the full extent of the academic dishonesty, but they want to uphold state-testing standards and have ask us to remove the 9th graders math and reading grades from the analysis.

## Challenge
## Secondary objective
To help Maria and her supervisor by generating new report with replacing 9th grade's reading score and math score with NaN value and find the new findings for Thomas High School.

### How is the district summary affected?
During the analysis we uncovered that there was relativily small drop in the average math and reading scores, and overall averages.

Note: the summary before removing the THS 9th grader;
![school_district_summary_w_THS_9th  revised](https://user-images.githubusercontent.com/82338072/119266805-360c0280-bbba-11eb-9259-d7ee75553659.PNG)
And the summary after;
![school_district_summary_wo_THS_9th revised](https://user-images.githubusercontent.com/82338072/119266831-5340d100-bbba-11eb-9ce9-4097a1708f25.PNG)

As you can see the average math score drop from 78.99 to 78.93; the reading went from 81.88 to 81.86 and overall passing percentages follow suit with average passing percentage on math and reading going from 74.98 and 85.81 to 74.76 and 85.66.

## How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
![School_Summary_w_THS_9th_revised](https://user-images.githubusercontent.com/82338072/119266843-65bb0a80-bbba-11eb-90d1-fe1f3d386fac.PNG)
Before removal of the Thomas High School 9th graders scores the overall passing score was 65.07 with average math score 83.35, average reading score 83.89%, passing math 66.91%, passing reading score 69.66.
![School_Summary_wo_THS_9th_revised](https://user-images.githubusercontent.com/82338072/119266849-6ce21880-bbba-11eb-829a-ffcc4137bdc8.PNG)
After removing the THS 9th graders from the calculations the grades changed to an overall passing percentage 90.63% with an average math score of 83.35% and a average reading score of 83.73%.  

## Result after replacing the ninth-grade scores
Here is a snapshot of the Math and Reading scores by grades.
Reading Summary
![Reading_Summary](https://user-images.githubusercontent.com/82338072/119266870-7f5c5200-bbba-11eb-8bd8-06884383354a.PNG)

Math Summary
![Math_Summary](https://user-images.githubusercontent.com/82338072/119266881-897e5080-bbba-11eb-8b0d-5ed62bb73ccc.PNG)

There are minimal differences between the schools other than the THS 9th graders that are missing because they were NAN from the summary.

## Scores by school spending
Our analysis shows the most effective spending amount came out to less than $584 per student. Turned out as the school district spent more money the overall school performance decreased.
![School_Spending](https://user-images.githubusercontent.com/82338072/119266902-9a2ec680-bbba-11eb-93c7-6dac3b8f2a1f.PNG)

## Scores by school size
The overall passing scores were better with the smaller the school size. Our analysis shows as the school got bigger in size the overall passing score decreased.
![School_BY_Population](https://user-images.githubusercontent.com/82338072/119266907-a0bd3e00-bbba-11eb-8735-7645bfff8f42.PNG)

## Scores by school type
The overall passing performance from the charter school is far better that district school. I found that the overall district school results were not affected after the replacing NaN values for THS 9th graders.
![grades_by_school_type](https://user-images.githubusercontent.com/82338072/119266922-af0b5a00-bbba-11eb-9f5c-826c140b6909.PNG)








