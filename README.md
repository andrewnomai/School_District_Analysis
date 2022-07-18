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
- Percentage of Passing Reading went from **86** to **85.7
- Overall Passing Percentage went from **65** to **64.9

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

Replacing 9th Graders Scores clearly affects Thomas High School's performance relative to other schools because there has been a significant shift within the ranks of the top performing schools, with Thomas High School previously as one of the top performing schools however, after the data cleanup, this positioned Thomas High School much lower down the rankings of the data set. *Image 1* shows the data before the clean up of the top 5 schools, while *Image 2* shows the data afterwards. *Image 3* shows the bottom 5 schools before the clean up and *Image 4* shows the data afterwards.  

**PyCitySchoolsData ORIGINAL** *Image 1*

![PyCitySchools_Top5Schools](https://user-images.githubusercontent.com/107603065/179452375-3ed11b1d-0191-4ae7-b36b-ac85b4c06618.png)

**PyCitySchoolsDataChallenge REFACTORED** *Image 2*

![PyCitySchools_Challenge_Top5Schools](https://user-images.githubusercontent.com/107603065/179452400-221974f5-5d51-4d44-83fa-9613530025cd.png)

**PyCitySchoolsData ORIGINAL** *Image 3*

![PyCitySchools_Bottom5Schools](https://user-images.githubusercontent.com/107603065/179452733-b88b0c8c-779f-40df-95bd-e6e521102c10.png)

**PyCitySchoolsDataChallenge REFACTORED** *Image 4*

![PyCitySchools_Challenge_Bottom5Schools](https://user-images.githubusercontent.com/107603065/179452747-dbb63208-d525-4d8c-9b19-f83bbb774c5d.png)


    
## Summary

