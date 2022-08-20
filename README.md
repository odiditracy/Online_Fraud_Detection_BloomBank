# Online Fraud Detection Bloom Bank
In 2018, fraud cost the world economy £3.2 trillion, according to Infosecurity Magazine. Fraud losses for some companies might amount to more than 10% of their overall expenses. 
Such significant losses encourage businesses to look for fresh ways to avoid, catch, and get rid of fraud. The most effective technology tool to combat financial fraud yet is machine learning.
Blossom Bank also known as BB PLC is a multinational financial services group, that offers retail and investment banking, pension management, asset management and payments services, headquartered in London, UK. Blossom Bank wants to build a Machine Learning model to predict online payment fraud. At the end of this project, we should be able to:
- Effectively detect and identify anomalies in the transactions that would normaly be undetected using traditional methods
- Improve it's cyber sercurity policies.
- Solidify the trust in the platform and amongst their customers by preventing fraudulent transactions.
This Readme section is to walk you through my codes and processes and will be useful to Data Analysts and Scientist. For the Stakeholder's report and insights, check the Stakeholders Report PDF or watch the presentation 
https://www.canva.com/design/DAFJ42pgpa0/iIWrYkH_auv3R8Z1W1slTA/view?utm_content=DAFJ42pgpa0&utm_campaign=designshare&utm_medium=link&utm_source=publishpresent#8
The dataset used was provided by Blossom Bank, a UK based bank. The transactional data set contained 10 columns and 1,048,575 rows.


# Methodology
1. Cleaning the data by deleting necessary rows or/and columns, performing exploratory data analysis, getting the relevant insights, and representing the data set using the most effective visualization charts.


2. Peforming Feature Engineering by encoding categorical variables. This implies that converting useful columns that are categorical into numerical columns so they can be featured or implemented in the machine learning model


3. Model selection and deployment. Interpreting the results of the modelling, determining which of the models best fit the data and also realistic in post production and finally recommending business strategies to help the bank avoid losing money to fraud.


# Data Cleaning and Exploratory Data Analysis
This project was conducted using Jupyter Notebook. After loading the appropriate libraries, I discovered there were no missing cells and that the data types of the variables (columns) of the necessary types 
I then went on to perform exploratory data analysis, gathering relevant insights as I went on and obtaining the right visualization charts. I then used boxplots, histograms, box plots, piecharts, distribution charts, pairplots, and heatmaps to visualize the data.
Please refer to the jupyter file for more technical details and the Stakeholders PDF for business summary and recommendations.


# Feature Engineering.
I observed that some columns would not be processed during the deployment of the models becuse that were categorical hence my decision to convert them to numerical values (encoding).
The nameOrg and nameDest were deleted because they had no significant importance in our models and I encoded the type column by creating 5 dummy columns being that there are 5 unique values in the type column.


# Model Deployment
I deployed unsupervised machine learning models (classification and regression) Linear Regression, Random Forest and Decision Tree. Of the 3 models, Random Forest was the most accurate at detecting fraudulent transactions.
Also, the confusion matrix also showed that it had the best results post production as well.


# Conclusion
Based on the insights and recommendations in the Stakeholders Report, if implemented, the bank will effectively detect and identify anomalies in the transactions that would normaly be undetected using traditional methods 
and also imporve it's banking practices.






