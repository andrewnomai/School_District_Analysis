# School_District_Analysis
## Project Overview
Cheif Data Scientist Maria is responsible for analyzing information for city school districts. She is tasked with preparing all standardized test data for analysis, reporting and presentation to provide insights about performance trends and patterns within the city schools. These insights are used to inform discussions and strategic decisions at the school and district level. We are tasked with assisting Maria in analyzing data on student funding and students' standardized test scores in order to aggregate such data to showcase trends in school performance. This analysis is designed to assist the school board and superindendent in making decisions regarding the school budgets and priorities. Additionally, the school board has notified Maria and her supervisor that part of the original data shows evidence of academic dishonesty by which reading and math grades for ninth graders of Thomas High School appear to have been altered. As this causes a discrepancy within the data, we are tasked to conduct a second analysis replacing Thomas High School's reading and math values with NaNs and report how these changes affected the overall anaylsis. 

## Resources
- Data Source: PyCitySchools.ipynb 
- Software: Python, Anaconda, Jupyter Notebook, Pandas

## Results
- ##### District Summary

**PyCitySchoolsData ORIGINAL**

![PyCitySchools_DistrictSummary](https://user-images.githubusercontent.com/107603065/179449144-daa6f533-7fad-40e8-80f1-cae7b275e883.png)


**PyCitySchoolsDataChallenge REFACTORED** 

![PyCitySchools_Challenge_DistrictSummary](https://user-images.githubusercontent.com/107603065/179449188-395464ba-a960-481b-997f-92bc478da7d4.png)

- Average Math Score went from **79.0** to **78.9**
- Average Reading Score remained at 81.9
- Percentage of Passing Math went from 75 to 74.8
- Percentage of Passing Reading went from 86 to 85.7
- Overall Passing Percentage went from 65 to 64.9

The district summary has been slightly affected due to the refactored data but not by much. This would unlikely cause an issue regarding performance trends within the district as the change is minimal.

- ##### School Summary
 
**PyCitySchoolsData ORIGINAL** 

![PyCitySchools_SchoolSummary](https://user-images.githubusercontent.com/107603065/179449295-41ce2d2a-8b2a-4e1a-993b-48a426dd4cfa.png)

**PyCitySchoolsDataChallenge REFACTORED**

![PyCitySchools_Challenge_SchoolSummary](https://user-images.githubusercontent.com/107603065/179449307-b70ab258-48ee-495c-adfd-67036d592dea.png)

- Average Math Score at Thomas High went from **79.0** to **78.9**
- Average Reading Score at Thomas High went from 
- Percentage of Passing Math at Thomas High went from 75 to 74.8
- Percentage of Passing Reading at Thomas High went from 86 to 85.7
- Overall Passing Percentage at Thomas High went from 65 to 64.9


  
  - ##### Replacing 9th Graders Scores
    - 
    
## Summary

