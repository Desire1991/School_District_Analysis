# School_District_Analysis

SCHOOL DISTRICT ANALYSIS PROJECT

Project Overview

Basically, this project is based on Thomas High School one of the School in School District where the school board was not happy about the analysis made by their school district. The School District Analysis report for 9th grade's reading score and math score results contain some evidence of academic dishonesty. 

Objective of the project:

The task here will be to replace Math and reading scores for Thomas High School with the NaN while keeping the rest of the data intact. And then helping out showing how the changes affected the overall analysis.

Results:
The following are results from the analysis made after the changes:
•	How is the district summary affected?
	The district summary is affected by a small amount where avg math scores went from 78.98 to 78.93, and avg reading scores went from 81.87 to 81.85, and the 3 metrics of Percentages of passing all dropped about 1%

Image showing the district summary

<img width="1008" alt="Screen Shot 2021-01-21 at 3 00 19 AM" src="https://user-images.githubusercontent.com/74233163/105352432-7e3afa00-5bb3-11eb-834d-8e31435d1d10.png">

How is the school summary affected?

Only the Thomas High school number are affected as expected, while average scores of math and reading were affected less than 1%, % of passing math and reading, as well as overall passing decreased significantly. The 3 later metrics dropped from 90th percentile to 60th percentile.
		
school summary image showing


<img width="947" alt="District_summary_df" src="https://user-images.githubusercontent.com/74233163/105349755-c6581d80-5baf-11eb-8f0e-0437db6782af.png">



   How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance, relative to the other school 

   .The most notable changes are that % passing read, math, and overall decreased. 
   .we evaluate the school by % Overall Passing, then Thomas High School went from 2nd place to 8th place out of 15 schools.

Image showing the results


How does replacing the ninth-grade scores affect the following:
Math and Reading Scores by Grade

<img width="694" alt="reading_score_ByGrade" src="https://user-images.githubusercontent.com/74233163/105349976-16cf7b00-5bb0-11eb-8f3e-88ef81deed1c.png">

Scores by School Spending

<img width="828" alt="Spending_summary_df" src="https://user-images.githubusercontent.com/74233163/105348406-e7b80a00-5bad-11eb-84f7-2362049969c0.png">


The analysis here shows that the less money spent was less than $584
Thomas High School's spending is not affected, nor is school size and type. However, as the data changed, it painted a very different picture. 

While the Math and Reading scores by grade on overall data is affected very little, it lowered the school spending type between $630-644 per student on passing, which is the spending range that Thomas school is in.

It also lowers the same metrics, % passing and overall passing, more notably in the medium school size (1000-2000).
Finally, it also affected the same metrics more notably for Charter schools. The actual values can be extracted by the jupyter notebook in python result/output.




Scores by School Size:
The reserch suggests that overall passing score is better with the smaller the school size. As we have bigger the school size the overall passing score           decreases slowly.
      
Image showing the results


<img width="767" alt="size_summary_Df" src="https://user-images.githubusercontent.com/74233163/105349648-a6285e80-5baf-11eb-8192-abc9e68fd152.png">



Scores by School Type
Image showing the results:

<img width="726" alt="type_summary_df" src="https://user-images.githubusercontent.com/74233163/105349898-f56e8f00-5baf-11eb-9fbe-b29e14f27e57.png">

The overall passing performance from the charter school is far better that district school.

The initial overall passing percentage is 90 with average math score 83.5, reading score 83.90, % math score 94 and % reading score 97. The final overall passing percentage is dropped to 87 with average score 83.5, reading score 83.9, % math score 90 and % reading score 93.
And ,the overall district school results not found affected after the replacing NaN values.
By replacing the Thomas High School 9th grade score, we changed only Thomas High School's read and math grades from around 83 percent to NaN.

Image showing after replacing using NaN:


<img width="632" alt="sttudent_data_ForNaN" src="https://user-images.githubusercontent.com/74233163/105349439-50ec4d00-5baf-11eb-9fd0-1983cec6b836.png">



Summary:

From the Disctrict School Analysis, we have found some following results. There is slight changes in overall passing result but it still has significant contribution to "Thomas High School" and results are found as:

  1.The original % of overall passing of Thomas High School was 90.94 % and it got dropped to 65.07.
  2.The original math score of Thomas High School was 83.41% and it got dropped to 83.35%.
  3.The original reading score of Thomas High School was 83.84% and it got dropped to 83.98%
  4.The original % passing Math score of Thomas High School was 93.27% and it got dropped to 66.91%

  The original % passing Reading Score of Thomas High School was 97.30% and it got dropped to 69.66%
       
 
 Image showing the summary

