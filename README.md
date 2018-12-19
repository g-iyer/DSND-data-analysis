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
  
  The notebook uses the IBM Telco dataset also available in this repository, named - **WA_Fn-UseC_-Telco-Customer-Churn.csv**
  
  Please download and save the notebook and data file to your folder to try. 
  

## Results

  The analysis revealed that 
                *clients with a long tenure did not leave*,
                *monthly and total charges had a direct relationship to churn* and 
                *those on month-to-month deals were more likely to leave*. 
                
  Please refer to the Jupyter Notebook for all the results and visualizations. Also see my blog at Medium here -> 
  
  The analysis was possible without the need to develop a ML model primarily because I treated this as a data analysis and inference project instead of a prediction problem. This dataset has been used in kaggle by many to try out predictive ML modeling. The IBM site (given above) has directions to execute their Watson studio ML algorithms to explore this dataset.
  
  ## Reflections
  
  This project helped me understand not only the data science and analysis process but also how **visualization (using matplotlib
  and seaborn)**  and **inference (using pandas functions)** can be very helpful in understanding data. 
  As mentioned in the coursework data science is not always about "Machine Learning" !
    
  I plan to use the visualization techniques that I learnt in this project in my regular work. It was a challenge to understand
  and use the syntax of these plotting packages but the results are worth it. 
    
 ## Acknowledgments
  
  Thanks to IBM for providing the dataset and to the many programmers and data scientists on sites like kaggle and stackoverflow.
   
   
