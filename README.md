# School_District_Analysis

SCHOOL DISTRICT ANALYSIS PROJECT

Project Overview

Basically, this project is based on Thomas High School one of the School in School District where the school board was not happy about the analysis made by their school district. The School District Analysis report for 9th grade's reading score and math score results contain some evidence of academic dishonesty. 

Objective of the project:

The task here will be to replace Math and reading scores for Thomas High School with the NaN while keeping the rest of the data intact. And then helping out showing how the changes affected the overall analysis.

Results:
The following are results from the analysis made after the changes:
•	How is the district summary affected?
	The district summary is affected by a small amount where avg math scores went from 78.98 to 78.93, and avg reading scores went from 81.87 to 81.85, and the 3     metrics of Percentages of passing all dropped about 1%

Image showing the district summary



•	How is the school summary affected?

           Only the Thomas High school number are affected as expected, while average scores of math and reading were affected less than 1%, % of passing math and reading, as well as overall passing decreased significantly. The 3 later metrics dropped from 90th percentile to 60th percentile.
		
school summary image showing






•	How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance, relative to the other school 

     o	The most notable changes are that % passing read, math, and overall decreased. 
     o	we evaluate the school by % Overall Passing, then Thomas High School went from 2nd place to 8th place out of 15 schools.

Image showing the results


•	How does replacing the ninth-grade scores affect the following:
o	Math and Reading Scores by Grade


o	Scores by School Spending
Image showing the results:
<img width="828" alt="Spending_summary_df" src="https://user-images.githubusercontent.com/74233163/105348406-e7b80a00-5bad-11eb-84f7-2362049969c0.png">


The analysis here shows that the less money spent was around




o	Scores by School Size:
      The reserch suggests that overall passing score is better with the smaller the school size. As we have bigger the school size the overall passing score           decreases slowly.
      
      Image showing the results



o	Scores by School Type
Image showing the results:


The overall passing performance from the charter school is far better that district school.

The initial overall passing percentage is 90 with average math score 83.5, reading score 83.90, % math score 94 and % reading score 97. The final overall passing percentage is dropped to 87 with average score 83.5, reading score 83.9, % math score 90 and % reading score 93.
And ,the overall district school results not found affected after the replacing NaN values.
By replacing the Thomas High School 9th grade score, we changed only Thomas High School's read and math grades from around 83 percent to NaN.

Image showing after replacing using NaN:


Thomas High School's spending is not affected, nor is school size and type. However, as the data changed, it painted a very different picture. 

While the Math and Reading scores by grade on overall data is affected very little, it lowered the school spending type between $630-644 per student on passing, which is the spending range that Thomas school is in.

It also lowers the same metrics, % passing and overall passing, more notably in the medium school size (1000-2000).
Finally, it also affected the same metrics more notably for Charter schools. The actual values can be extracted by the jupyter notebook in python result/output.




Summary:

From the Disctrict School Analysis, we have found some following results. There is slight changes in overall passing result but it still has significant contribution to "Thomas High School" and results are found as

     1.The original % of overall passing of Thomas High School was 90.94 % and it got dropped to 65.07.
     2.The original math score of Thomas High School was 83.41% and it got dropped to 83.35%.
     3.The original reading score of Thomas High School was 83.84% and it got dropped to 83.98%
     4.The original % passing Math score of Thomas High School was 93.27% and it got dropped to 66.91%
       The original % passing Reading Score of Thomas High School was 97.30% and it got dropped to 69.66%
       
       Image showing the summary

