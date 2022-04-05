# Lending Club Case Study
> To understand the important features for Lending Club to minimize the credit risk.


## Table of Contents
* [General Info](#general-information)
* [Data Cleaning](#technologies-used)
* [Data Visualization](#technologies-used)
* [Conclusions](#conclusions)


<!-- You can include any other section that is pertinent to your problem -->

## General Information

- What is the background of your project?<br>
Lending Club is a marketplace for personal loans that matches borrowers who are seeking a loan with investors looking to lend money and make a return.
A consumer finance company which specializes in lending various types of loans to urban customers, when receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. 
Two types of risks are associated with the bank’s decision:
>1. If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
>2. If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company.
The company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment.



- What is the business probem that your project is trying to solve?<br>
>The aim of the project is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc. 



- What is the dataset that is being used?<br>
>Dataset is available in “.csv” format.
>We are having the data of past customers who got approval for loan and along with their loan status , either they paid the full loan amount with interest, currently paying or they didn’t pay the loan and charged off.
>Our dataset have around 39717 customer’s past data with 111 different information of each for analysis.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Conclusions

- **Univariate Analysis:**

1. The analysis of each variable individually is done.<br>
2. Missing Values are handled by either dropping or imputing.<br>
3. Identification of Important variable with case study point of view.<br>
4. The Outlier detection and their treatment is done.<br>
5. The variables are converted into their correct datatype.<br>
6. Derived variables added.<br>


- **Bivariate Analysis:**

1. The behaviour of each variable w.r.t target variable.<br>
2. The relationship between Independent and dependent variables whether they are directly proportional or indirectly proportional or no relation between them.<br>
3. Impact of features of credit risk.<br>


- **Multivariate Analysis:**

1. The correlation of variables one to one.
2. Identification of highly correlated variables and non correlated variables.
3. Visualization using pairplot.<br>

- **Final Conclusion:**

At the end of Exploratory Data Analysis (EDA) part, we have identified the top most important features from the dataset (out of 111 features) given below:<br>
1. Annual income
2. Loan Amount
3. Purpose
4. Term 
5. Grade
6. Interest Rate
7. Installment
8. Debt-to-income

These top 8 features will help the business to minimize the defaulters rate and this will increases the business financial growth by approving loan of good customers who repays the loan within time.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- pandas - version 1.3.4
- numpy - version  1.20.3
- matplotlib - version 3.4.3
- seaborn - version  0.11.2
- plotly - version  5.6.0


## Contact
Created by [@poornimanikam] - feel free to contact me!

