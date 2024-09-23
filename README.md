# Lending Club Case Study
> A consumer finance company needs to minimize financial losses due to loan defaults. By analyzing historical loan data, the company aims to identify patterns and factors that indicate a higher likelihood of default. This information will enable them to make informed decisions about loan approvals, interest rates, and risk mitigation strategies.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
**- Business Understanding**

You work for a consumer finance company which specializes in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:
If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company

- **What is the background of your project?**

<img src="https://drive.google.com/uc?id=1rJoD5XqK-cBL6dWKEqyjEHKY5PhxTsl2" alt="My Google Drive File ID" />

In this case study, you will use EDA to understand how consumer attributes and loan attributes influence the tendency of default.

Loan accepted: If the company approves the loan, there are 3 possible scenarios described below:
**Fully paid:** Applicant has fully paid the loan (the principal and the interest rate)
**Current:** Applicant is in the process of paying the installments, i.e. the tenure of the loan is not yet completed. These candidates are not labeled as 'defaulted'.
**Charged-off:** Applicant has not paid the installments in due time for a long period of time, i.e. he/she has defaulted on the loan 
**Loan rejected:** The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)

**- What is the business probem that your project is trying to solve?**
This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. 
 
Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'. 
 
If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.
 
In other words, the company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  The company can utilize this knowledge for its portfolio and risk assessment. 

To develop your understanding of the domain, you are advised to independently research a little about risk analytics (understanding the types of variables and their significance should be enough).

**- What is the dataset that is being used?**
loan 2.csv which includes all data used for this case study.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions

**1. Loan Purpose Matters:** There are many debt consolidation loans but at greater danger of default. The other purposes of loans bring varying risks.
Verification is Everything: The verification of consumer's information reduces the risk of default as much as possible. Loans that are labeled 'Verified' are the best; those labeled 'Not Verified' have the highest charge-off rates.

**2. Income Does Not Isolate:** Income alone does not predict the performance of a loan. Rich-income consumers can still default, and so such factors as credit history and debt-to-income are more important to know.

**3. Interest Rates Are in Line with the Credit Grade:** Interest rates are positively correlated with the credit grade, and this tells about the risk-based pricing. High-risk consumers have poor grades and the interest rates are higher.
States Differ from Each Other with Respect to Volume and Defaults: States would vary with regards to the volume of loan as well as default rates. This may be due to regional economic condition and demographics.

**4. Interdependence Between Features:** The pairplot and the correlation heatmap reveal high interdependence among various attributes. Analysis relating to such dependency would be quite intricate.
With this knowledge and guidance, the company will be in a better position to make informed decisions regarding lending, reduce potential losses from bad credit, and improve overall performances in portfolios.


**Recommendations :**
1. Risk Assessment Models be made more accurate by incorporating loan purpose and verification status into risk assessment models.

2. Purpose-Specific Underwriting Policies: Develop underwriting policies that include only high-risk loan purposes, such as debt consolidation. Such policies are bound to have higher qualification cut-offs or interest rates.

3. Verify First: Make the borrowers realize the importance of verification and realise that complete and verifiable information will help them get lower interest rates.

4. Track Local Trends: Review state-by-state loan performance and economic conditions to spot local trends in the emergence of risks or opportunities.

5. More in-depth Analysis: Analyze loan attributes and default risk more deeply to explore complex relationships. This may involve advanced statistical techniques or machine learning models.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
Python Libraries

1.numpy

2.pandas

3.matplot

4.seaborn

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by upGrad


## Contact
Created by https://github.com/RohitKini - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
