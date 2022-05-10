# Project Name
> Lending Club Case Study: We have lending loan data of consumer finance company which are providing various type of loan to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile.
1. If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company.
2. If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company.
The data given contains the information about past loan applicants and whether they ‘defaulted’ or not. The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.


## Table of Contents
* [General Info](#We have history data set. So we have perorm some data cleansing, sanity, data visualization process here using Univariate and Multivariate analysis)
* [Technologies Used](# We achieved all data visualization via EDA using Python as a language)
* [Conclusions](#We have identified what would be the analysis we can improve here like we have to do some extra analysis on small business etc. )

<!-- You can include any other section that is pertinent to your problem -->

## General Information
Problems: I have lending loan data of consumer finance company which are providing various type of loan to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:
1. If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company.
2. If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company.
The data given contains the information about past loan applicants and whether they ‘defaulted’ or not. The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.
I will use EDA to understand how consumer attributes and loan attributes influence the tendency of default.
When a person applies for a loan, there are two types of decisions that could be taken by the company:
1. Loan accepted: If the company approves the loan, there are 3 possible scenarios described below:
1.1. Fully paid: Applicant has fully paid the loan (the principal and the interest rate)
1.2. Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.
1.3. Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan
2. Loan rejected: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)¶

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
1. Defaulter rate is higher when employee length are 1 year, 7 years, and >=10 years.
2. Minimum defaulter rate exist for 9 years employee length.
3. Maximum defaulter rate for emp length >=10 years.
4. Grade is propotonal to Loan Defaulter Probability.
5. We can see that , most of the loan default probablity is seen for small_business,so bank should be extra careful while approving the loan for such businesses
6. Minimum defaulter rate showing for Major Purchase purpose.
7. We can see, as annual income is @[proportional to] probability of being defaulter.It is reaching up to 19%
8. We can see that as interest rate is increasing chance of being defaulter is also increased. when the interest rate touches more than 15% , risk of default rate is increasing¶
9. We can see that default rate is increasing , when the loan amount/funded amount is increasing at the alarming rate

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- library - pandas
- library - matplotlib
- library - plotly

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


## Contact
Created by [@githubusername] - feel free to contact me[]!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->