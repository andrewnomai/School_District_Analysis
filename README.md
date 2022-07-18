# School_District_Analysis
## Project Overview
Cheif Data Scientist Maria is responsible for analyzing information for city school districts. She is tasked with preparing all standardized test data for analysis, reporting and presentation to provide insights about performance trends and patterns within the city schools. These insights are used to inform discussions and strategic decisions at the school and district level. We are tasked with assisting Maria in analyzing data on student funding and students' standardized test scores in order to aggregate such data to showcase trends in school performance. This analysis is designed to assist the school board and superindendent in making decisions regarding the school budgets and priorities. Additionally, the school board has notified Maria and her supervisor that part of the original data shows evidence of academic dishonesty by which reading and math grades for ninth graders of Thomas High School appear to have been altered. As this causes a discrepancy within the data, we are tasked to conduct a second analysis replacing Thomas High School's reading and math values with NaNs and report how these changes affected the overall anaylsis. 

## Resources
- Data Source: PyCitySchools.ipynb 
- Software: Python, Anaconda, Jupyter Notebook, Pandas

# Results
## District Summary

**PyCitySchoolsData ORIGINAL**

![PyCitySchools_DistrictSummary](https://user-images.githubusercontent.com/107603065/179451204-08e81e36-2228-400e-ad15-6fcfe092afc9.png)


**PyCitySchoolsDataChallenge REFACTORED** 

![PyCitySchools_Challenge_DistrictSummary](https://user-images.githubusercontent.com/107603065/179449188-395464ba-a960-481b-997f-92bc478da7d4.png)

- Average Math Score went from **79.0** to **78.9**
- Average Reading Score remained at **81.9**
- Percentage of Passing Math went from **75** to **74.8**
- Percentage of Passing Reading went from **86** to **85.7**
- Overall Passing Percentage went from **65** to **64.9**

The district summary has been slightly affected due to the refactored data but not by much. This would unlikely cause an issue regarding performance trends within the district as the change is minimal.

## School Summary
 
**PyCitySchoolsData ORIGINAL** 

![PyCitySchools_SchoolSummary](https://user-images.githubusercontent.com/107603065/179451153-879fbe84-ae90-4049-ba1d-673514685b54.png)


**PyCitySchoolsDataChallenge REFACTORED**

![PyCitySchools_Challenge_SchoolSummary](https://user-images.githubusercontent.com/107603065/179449307-b70ab258-48ee-495c-adfd-67036d592dea.png)

- Percentage of Passing Math went from approximately **93%** to **67%**
- Percentage of Passing Reading went from approximately **97%** to **69%**
- Overall Passing Percentage went from approximately **91%** to **65%**

Within the school district summary, Thomas High School's data has largely been affected, specifically the passing percentage of math, reading, and overall. As a result of fixing the discrepency with the previous data set, the data from Thomas High reflects the percentage of scores excluding academic dishonesty. This allows for a more accurate analysis within the school. 
  
## Replacing 9th Graders Scores

##### Thomas High Performance Relative to Other Schools

Replacing 9th Graders Scores clearly affects Thomas High School's performance relative to other schools because there has been a significant shift within the ranks of the top performing schools, with Thomas High School previously as one of the top performing schools however, after the data cleanup, this positioned Thomas High School much lower down the rankings of the data set. *Image 1* shows the data before the clean up of the top 5 schools, while *Image 2* shows the data afterwards.

**PyCitySchoolsData ORIGINAL** *Image 1*

![PyCitySchools_Top5Schools](https://user-images.githubusercontent.com/107603065/179452375-3ed11b1d-0191-4ae7-b36b-ac85b4c06618.png)

**PyCitySchoolsDataChallenge REFACTORED** *Image 2*

![PyCitySchools_Challenge_Top5Schools](https://user-images.githubusercontent.com/107603065/179452400-221974f5-5d51-4d44-83fa-9613530025cd.png)


##### Math and Reading Perforamnce by Grade

**PyCitySchoolsData ORIGINAL** *MATH*

![PyCitySchools_MathScoresByGrade](https://user-images.githubusercontent.com/107603065/179453713-f2794ac0-f725-4650-99e7-d56a5e7bea53.png)

**PyCitySchoolsDataChallenge REFACTORED** *MATH*

![PyCitySchools_Challenge_MathScoresByGrade](https://user-images.githubusercontent.com/107603065/179453754-47300366-8b17-45db-86fe-7ae879fa0fa1.png)

**PyCitySchoolsData ORIGINAL** *READING*

![PyCitySchools_ReadingScoresByGrade](https://user-images.githubusercontent.com/107603065/179453845-609f0af8-e61a-4b49-a3c4-f68442bdafd2.png)

**PyCitySchoolsDataChallenge REFACTORED** *READING*

![PyCitySchools_Challenge_ReadingScoresByGrade](https://user-images.githubusercontent.com/107603065/179453870-4104003b-f0b0-48cd-bbb7-4bc0ba70e3b9.png)

The dataset for math and reading scores by grade do not change much apart from Thomas High School with replaces an actual numerical value with NaN. Compared to the other schools, the data is still the same. 


##### Scores by Spending

**PyCitySchoolsData ORIGINAL**

![PyCitySchools_SpendingSummary](https://user-images.githubusercontent.com/107603065/179454201-e60afaf3-eee5-4f05-b569-4a02f0aa867a.png)

**PyCitySchoolsDataChallenge REFACTORED**

![PyCitySchools_Challenge_SpendingSummary](https://user-images.githubusercontent.com/107603065/179454209-c23ac128-ed25-4d95-bb1d-b282851eb7ce.png)

The dataset for spending did not change due to the dataset not including the agent of discrepancy among the data which is the ninth-graders from Thomas High School. Therefore, this piece of information was not used to performance any analysis and therefore has not caused any changes amongst the data. 

##### Scores by Size

**PyCitySchoolsData ORIGINAL**

![PyCitySchools_SizeSummary](https://user-images.githubusercontent.com/107603065/179454405-f5ec348f-224e-4af6-9ee5-3d254baf3d90.png)

**PyCitySchoolsDataChallenge REFACTORED**

![PyCitySchools_Challenge_SizeSummary](https://user-images.githubusercontent.com/107603065/179454422-1bcc5c29-1ca5-4091-a5cd-5d8c05a83489.png)

Similarly to the previous section, the data within the dataset did not change due to the discrepency among the data not being included in this set to alter or cause any difference in the anaylsis.

##### Scores by Type

**PyCitySchoolsData ORIGINAL**

![PyCitySchools_TypeSummary](https://user-images.githubusercontent.com/107603065/179454480-27321694-44ba-4121-97b5-9be696c0184b.png)

**PyCitySchoolsDataChallenge REFACTORED**

![PyCitySchools_Challenge_TypeSummary](https://user-images.githubusercontent.com/107603065/179454464-3afb99a1-51ba-4ae6-aa90-01afb94d6897.png)

Similarly to the previous section, the data within the dataset did not change due to the discrepency among the data not being included in this set to alter or cause any difference in the anaylsis.
    
## Summary

##### Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

1. The math, reading, and overall passing percentage for Thomas High School significantly drops as a result of the replacement. 
2. As a result of the replacement, the drop in percentage causes Thomas High School to drop from the top high performing schools.
3. To counter the discrepancy, we fixed the data to perform an anaylsis from Thomas High's 10th to 12th graders.
4. With the absence of the ninth grader discrepancy, Thomas High rises as one of the top performing school. 
