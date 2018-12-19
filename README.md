# DSND-data-analysis

## Introduction and project motivation

  Welcome my  Udacity Data Science Nanodegree "Write A Data Science blog post" project site on GitHub. 
  
  I have analyzed a dataset made available by IBM about a Telecom company. It is available under the title "Using Customer Behavior Data to Improve Customer Retention" here [link to IBM](https://www.ibm.com/communities/analytics/watson-analytics-blog/predictive-insights-in-the-telco-customer-churn-data-set/)
  
  This dataset contains client data with many features one of which is "Churn" - this indicates if that client has left or stayed. As given on IBM's site:
    "A telecommunications company is concerned about the number of customers leaving their landline business for cable competitors.
     They need to understand who is leaving. Imagine that you’re an analyst at this company and you have to find out who is leaving and why."
  
  I have used data analysis and visualization techniques to understand and report on the data. It can been seen that client behavior inference can be done using simple techniques. Use of machine learning will enhance the inference but has not been attempted here. 
  
  
## Implementation
  The data analysis was done in a Jupyter notebook with Python 3.2. I used the following libraries/packages in the process 
    - pandas, numpy, matplotlib, seaborn, and Warnings.
   
  The notebook *Telco customer churn analysis.ipynb)* is available here in my GitHub repository [Data Analysis Project link](https://github.com/g-iyer/DSND-data-analysis) 
  The notebook uses the IBM Telco dataset also available in this repository, named - WA_Fn-UseC_-Telco-Customer-Churn.csv
  
  Please download and save the notebook and data file to your folder to try. 
  

## Observations

  The analysis revealed that clients with a long tenure did not leave, monthly and total charges had a direct relationship to churn and those on month-to-month deals were more likely to leave. 
  
  The analysis was possible without a need to develop a ML model primarily because I treated this as a data analysis and inference project instead of a prediction problem. This dataset has been used in kaggle by many to try out predictive ML modeling. 
   
   
   
  
Project Motivation
The motivation behind this analysis is to explore how data scientists compare with other non-data scientist software developers ("non-data scientists") with regard to demographics, programming languages used, coding experience and job satisfaction. Consequently, in this analysis, I set out to answer the following questions, using data collected by Stack Overflow as part of their 2018 Annual Developer Survey:
1.	How does the demographic profile of data scientists differ from that of non-data scientists?
2.	What programming languages do data scientists favour and how do they differ from those used by non-data scientists?
3.	How much coding experience do data scientists have compared to non-data scientists?
4.	Are data scientists more satisfied with their jobs/careers than non-data scientists?
File Descriptions
All analysis is contained in the Jupyter notebook DS Survey Analysis.ipynb.
To run this code, it is first necessary to download the 2018 Stack Overflow Develop Survey dataset from https://insights.stackoverflow.com/survey. The folder containing this data (developer_survey_2018) should then be saved in the current working directory in a folder named "Data".
Results
The main findings of this analysis are summarised in a blog post available here.
Licensing, Authors, Acknowledgements
The dataset used in this analysis was created by Stack Overflow and made available for download under the Open Database License (ODbL).
The code contained in this repository may be used freely with acknowledgement.
