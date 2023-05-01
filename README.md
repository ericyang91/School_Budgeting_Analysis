# School Budgeting Analysis
</br>

## Purpose:

  The purpose of this project is to analyze the district-wide standardized test results of students in PyCity, an imaginary city, to help the school board and mayor make strategic decisions regarding future school budgets and projects. The data includes every student’s standardized math and reading scores, as well as various information on the schools they attend. The project explores district, school, subject, and budget-wide trend in order to assist with future decision making.

## Data:

  A quick snapshot of the raw DataFrame:
</br></br>
<p align="center">
  <img src="https://github.com/ericyang91/School_Budgeting_Analysis/blob/main/Images/rawdata.png" alt="rawdata"/>
</p>
</br>

## Observations:
</br>
District Summary:
</br>
</br>
<p align="center">
  <img src="https://github.com/ericyang91/School_Budgeting_Analysis/blob/main/Images/districtsummary.png" alt="districtsummary"/>
</p>
</br>
School Summary:
</br>
</br>
<p align="center">
  <img src="https://github.com/ericyang91/School_Budgeting_Analysis/blob/main/Images/schoolsummary.png" alt="schoolsummary"/>
</p>
</br>
Highest Performing Schools by % Passing Both Subjects:
</br>
</br>
<p align="center">
  <img src="https://github.com/ericyang91/School_Budgeting_Analysis/blob/main/Images/highestperforming.png" alt="highestperforming"/>
</p>
</br>
Lowest Performing Schools by % Passing Both Subjects:
</br>
</br>
<p align="center">
  <img src="https://github.com/ericyang91/School_Budgeting_Analysis/blob/main/Images/lowestperforming.png" alt="lowestperforming"/>
</p>
</br>
Math Scores by Grade:
</br>
</br>
<p align="center">
  <img src="https://github.com/ericyang91/School_Budgeting_Analysis/blob/main/Images/mathbygrade.png" alt="mathbygrade"/>
</p>
</br>
Reading Scores by Grade:
</br>
</br>
<p align="center">
  <img src="https://github.com/ericyang91/School_Budgeting_Analysis/blob/main/Images/readingbygrade.png" alt="readingbygrade"/>
</p>
</br>
Summary by Budget Category:
</br>
</br>
<p align="center">
  <img src="https://github.com/ericyang91/School_Budgeting_Analysis/blob/main/Images/summarybybudget.png" alt="summarybybudget"/>
</p>
</br>
Summary by Size Category:
</br>
</br>
<p align="center">
  <img src="https://github.com/ericyang91/School_Budgeting_Analysis/blob/main/Images/summarybysize.png" alt="summarybysize"/>
</p>
</br>
Summary by School Type:
</br>
</br>
<p align="center">
  <img src="https://github.com/ericyang91/School_Budgeting_Analysis/blob/main/Images/summarybytype.png" alt="summarybytype"/>
</p>
</br>

## Analysis:
</br>

- Top 5 performing schools as measured by % passing both math and reading are all charter schools, with the total number of students and budget below the district average. The statistical significance of the difference is subject to further testing.
- Top 5 performing schools as measured by % passing both math and reading have test scores above the district average. The statistical significance of the difference is subject to further testing.
- Bottom 5 performing schools as measured by % passing both math and reading are all district schools, with the total number of students and budget above the district average. The statistical significance of the difference is subject to further testing.
- Bottom 5 performing schools as measured by % passing both math and reading have test scores below the district average. The statistical significance of the difference is subject to further testing.
- Schools in the lower budget per student category have higher subject scores. The statistical significance is subject to further testing.
- Schools in the higher budget per student category have lower subject scores. The statistical significance is subject to further testing.
- Schools with small student population (less than 2,000) on average have higher test scores. The statistical significance is subject to further testing.
- Charter schools on average have higher test scores. The statistical significance is subject to further testing.
</br>
** The general trend is that charter schools that on average have smaller student population have higher math and reading scores compared to district schools. Charter schools also spend on average less budget per student. Further study is required separate the effect of school types from that of the population on students' performance. It is also important to explore if there are any other factors related to charter schools that are affecting students' performance. Before these studies are performed, it is recommended to be cautious before making strategic decisions on budgeting. **

</br>
</br>

## Languages and Libraries:
</br>

`python v.3.9.12`
`jupyter notebook v.6.4.8`
`pandas v.1.4.2`
`Visual Studio 1.74.1`
