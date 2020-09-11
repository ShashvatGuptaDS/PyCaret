# PyCaret
PyCaret is an open-source, low-code machine learning library in Python that does the heavy lifting for you right from data preparation to model deployment quickly by writing only a few lines of code.
PyCaret can be used for different machine learning projects ex- Classification, Regression, and Anomaly Detection. For instance, to create a decision tree model in PyCaret, only one line code is sufficient. You just need to be careful about passing the correct ID as a parameter. 
<pre> `Model= create_model('dt')`
</pre>
 
## Problem Definition

To detect and classify normal and fraudelent transaction based on the Credit Card Clients Dataset.

## Pre-Requisites
* Python 3.x
* The latest version of PyCaret
* Some understanding of ML

## Dataset used

In this tutorial we have used a dataset from UCI called Default of Credit Card Clients Dataset. This dataset contains information on default payments, demographic factors, credit data, payment history, and billing statements of credit card clients in Taiwan from April 2005 to September 2005. There are 24,000 samples and 25 features. Short descriptions of each column are as follows:

| Feature   |      Description  
|----------|:-------------:|
| ID |  ID of each client|
| LIMIT_BAL |   Amount of given credit in NT dollars (includes individual and family/supplementary credit)  |
| SEX | Gender (1=male, 2=female) |
| EDUCATION | (1=graduate school, 2=university, 3=high school, 4=others, 5=unknown, 6=unknown) |
| MARRIAGE |  Marital status (1=married, 2=single, 3=others) |
| AGE | Age in years |
| PAY_0 to PAY_6|  Repayment status by n months ago (PAY_0 = last month ... PAY_6 = 6 months ago) (Labels: -1=pay duly, 1=payment delay for one month, 2=payment delay for two months, ... 8=payment delay for eight months, 9=payment delay for nine months and above) |
| BILL_AMT1 to BILL_AMT6 | Amount of bill statement by n months ago ( BILL_AMT1 = last_month .. BILL_AMT6 = 6 months ago) |
| PAY_AMT1 to PAY_AMT6 | Amount of payment by n months ago ( BILL_AMT1 = last_month .. BILL_AMT6 = 6 months ago) |
| default | Default payment (1=yes, 0=no) Target Column |

Dataset Acknowledgement:
Lichman, M. (2013). UCI Machine Learning Repository. Irvine, CA: University of California, School of Information and Computer Science.
