**# Bank Loan EDA Project**
Overview
This project focuses on conducting an Exploratory Data Analysis (EDA) of a dataset related to bank loans using Python. The primary goal is to gain insights into the dataset, understand the loan application and approval process, and identify patterns and trends that can inform decision-making within the banking industry.

**Prerequisites**
To run this project, you need to have the following software and libraries installed on your system:
Python 3.x
Jupyter Notebook (optional but recommended)
Pandas
NumPy
Matplotlib
Seaborn

**Dataset**
The required dataset can be downloaded by following this link: https://drive.google.com/drive/folders/14IucJ_VPMskmd7ttMYKvgUaUIz30bJQy

There are 2 data files : 1.application_data 2. previous_application

**About the Project**

The goal of this project is to use Exploratory Data Analysis (EDA) to analyze loan application data and develop a basic understanding of risk analytics in banking and financial services. The data contains information about loan applications and is divided into two types of scenarios: clients with payment difficulties and all other cases.

The primary business objective of this project is to identify patterns that indicate whether a client has difficulty paying their installments, which may be used to take actions such as denying the loan, reducing the amount of loan, lending to risky applicants at a higher interest rate, etc. The aim is to ensure that consumers who are capable of repaying the loan are not rejected.

The approach for this analysis will involve identifying missing data and handling it appropriately, identifying outliers in the dataset, identifying data imbalances, and conducting univariate, segmented univariate, bivariate analysis, and other relevant statistical analyses.

In this report, we will present our findings from the analysis, including visualizations and insights that explain why certain variables are important in differentiating clients with payment difficulties from all other cases. We will also identify the top 10 correlations for clients with payment difficulties and all other cases.

Problem Statement:

Loan providing companies find it difficult to lend money to people due to their insufficient or non-existent credit history. This leads to some consumers taking advantage of the situation by becoming defaulters. In this case study, we work for a consumer finance lending institution that specializes in lending various types of loans to customers. We need to use EDA to analyze the patterns present in the data to ensure that the applicants capable of repaying the loan are not rejected.

When a client applies for a loan, the lending institution has to decide whether to approve or reject the application based on the applicant’s profile. Two types of risks are associated with the bank’s decision:

If the applicant is likely to repay the loan, not approving the loan results in a loss of business to the lending institution.

If the applicant is not likely to repay the loan, i.e., he/she is likely to default, then approving the loan may lead to a financial loss for the lending institution.

Missing Data:

The dataset contains missing data. We can handle the missing data by either removing the columns or replacing them with appropriate values. Since EDA does not necessarily require replacing the missing value, we can remove the columns with missing values from the analysis.

Outliers:

We will also identify any outliers in the dataset. Outliers are observations that fall significantly outside of the range of other observations in the dataset. They can have a significant impact on the results of our analysis, so it is important to identify and handle them appropriately.

Data Imbalance:

We will check for data imbalance in the dataset. Data imbalance occurs when one class of data is overrepresented, and another class is underrepresented. In this case, we will identify any data imbalances between clients with payment difficulties and all other cases. 

Analysis:

We will conduct univariate, segmented univariate, and bivariate analysis on the data to understand the driving factors behind loan default, i.e., the variables that are strong indicators of default. We will also find the top 10 correlations for the Client with payment difficulties and all other cases (Target variable).

The results of our analysis will be presented visually, and we will summarize the most important results in the presentation. Our insights will explain why the variable is important for differentiating clients with payment difficulties from all other cases.

Conclusion
The Bank Loan EDA Project provides a comprehensive understanding of the loan dataset and offers valuable insights for decision-making in the banking industry.

