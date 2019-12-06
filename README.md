# DDS-Final-Project
DDSAnalytics Talent Management Solution with Employee Attrition Study

Author: Yang Zhang

## Introduction
This study is on behalf of DDSAnalytics which is specialized in talent management solution for Forture 100 companies. 

Talent management is defined as the iterative process of developing and retaining employees. It may include workforce planning, employee training programs, identifying high-potential employees and reducing/preventing voluntary employee turnover (attrition). 

To gain a competitive edge over its competition, we as in DDSAnalytics is using advance data science technology to help with talent management. The first application, identified by the excutive leadership team is on it with predicting employee turnover.

The dataset has 36 explanatory variables describing rich information of employee and we are using it to predict the employee attrition and monthly incomes.

## Files
[ga.rmd](https://github.com/taniayzhan/Casestudy2/blob/master/Analysis/ga.Rmd): The RMarkdown file which is general data analysis document. It contains the EDA and two modeling portions, demonstrates how we achieved the results and gives explanations from the outputs.

[ga.html](https://github.com/taniayzhan/Casestudy2/blob/master/Analysis/ga.html): The knit html file for all the analysis.

[CaseStudy2_Presentation_YZhang.pptx](https://github.com/taniayzhan/Casestudy2/blob/master/Documents/CaseStudy2_Presentation_YZhang.pptx): Presentation slide deck with results displayed and elaborated.

[\Prediction](https://github.com/taniayzhan/Casestudy2/tree/master/Prediction) is the directory we stored the prediction data files.
-   [Case2_pred_attr.csv](https://github.com/taniayzhan/Casestudy2/blob/master/Prediction/Case2_pred_attr.csv): Predictions of attrition on 300 data points.
-   [Case2_pred_monthlyincome.csv](https://github.com/taniayzhan/Casestudy2/blob/master/Prediction/Case2_pred_monthlyincome.csv):  Predictions of monthly incomes on 300 data points.


## Conclusions

We use the employee dataset to do an EDA first, then further modeling the attrition using a few different criteria, identifying factors that related to attrition. The top factors related to attrition I identified within this analysis are:

-   Age/TotalWorkingYears

-   MonthlyIncome/JobRole

-   Overtime/DistancefromHome



The top factors related to monthly incomes I identified within this analysis are:

-   Job level

-   Job role

-   YearsatCompany/TotalWorkingYears



There are a few learning about the dataset:

-   It appears that sales has a higher attrition rate.

-   Factors related to work-life balance appear important to attrition.

-   No apparent gender differences are found in attrition and monthly incomes.



