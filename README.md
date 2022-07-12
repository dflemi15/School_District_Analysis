# School_District_Analysis

1.	Overview of the school district analysis: Explain the purpose of this analysis.

The purpose of this project is to provide a comprehensive analysis of High School data. Our analysis will consist of providing useful metrics on math and reading scores across myriad high schools in the PyCity schools’ network. For this analysis, we are tasked with removing the math and reading scores of the ninth-grade class for Thomas High School due to academic integrity violations. Once complete, we will provide new analysis on the new population of students generated.

2.	Results: Using bulleted lists and images of DataFrames as support, address the following questions.

-	How is the district summary affected?

The metrics for the district summary do not appear to be affected much as the averages for math, reading, and overall passing rates appear to be steady as illustrated by the images below:

Before
![image](https://user-images.githubusercontent.com/107585908/178472013-15f488c0-4fb8-4cc0-ba07-a5597aa46850.png)
 

After
![image](https://user-images.githubusercontent.com/107585908/178472034-f661cafa-c503-43e3-ada3-429de920e22b.png)
 

-	How is the school summary affected?

As predicted, the overall averages for Thomas High School in the per school summary are reduced slightly, with the exception of “Average Reading Score” which appears to increase slightly.

Before
![image](https://user-images.githubusercontent.com/107585908/178472054-cc3a69a4-6b32-4b86-b4dd-fb6e4246709a.png)
 
![image](https://user-images.githubusercontent.com/107585908/178472071-78af94b7-4bbd-4a36-8f14-6f0842904f5c.png)


After
![image](https://user-images.githubusercontent.com/107585908/178472116-6816be31-53f9-4d3d-8460-25f7dfb14bd6.png)

-	How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

By replacing the ninth graders’ math and reading scores, the adjustments to Thomas High School’s scores put them in the top five of performing schools as indicated by the following print of the top five schools:

![image](https://user-images.githubusercontent.com/107585908/178472215-b9f455b8-4ad6-428c-a365-a8499d63e0d0.png)

-	How does replacing the ninth-grade scores affect the following
o	Math and reading scores by grade
o	Scores by school spending
o	Scores by school size
o	Scores by school type

For the math and reading scored, the metrics would not change due to the independent nature of how these scores were calculated. Each of the other, however, they appear to only change fractionally as the outputs for each category appear to remain the same if the totals are format to march the reporting standard. I have provided an example below:

Before:
![image](https://user-images.githubusercontent.com/107585908/178472246-117f8612-68a8-48ff-83f6-ff6d5289daaa.png)
 
After:
![image](https://user-images.githubusercontent.com/107585908/178472264-ea2f1696-5374-4140-b2f6-580bd1fc4555.png)
 
According to the images, the “$631 – 645” spending group was the only group that was fractionally impacted by the removing of the ninth grade reading and math scores. These changes are consistent for the school size and type as well. The totals do not appear to change substantially enough to be considered in our analysis.

3.	Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

To summarize, the largest change that occurred when we removed the ninth-grade scores was that the overall reading and math scores for Thomas High School increased dramatically, catapulting the school into the top five performers. The other changes appeared to be marginal at best. The district summary, school summary, and school spending per student summary are an example of this. Each  


