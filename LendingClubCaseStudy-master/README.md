# Lending Club Case Study
* Lending Club is a marketplace for personal loans that matches borrowers who are seeking a loan with  investors looking to lend money and make a return where a company/bank given loan to a application based in their profile 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#Technologies-Used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Provide general information about your project here.
The data contains the information about past loan applicants and whether they ‘defaulted’ or not. The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.

- What is the background of your project?
> This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures.  Borrowers can easily access lower interest rate loans through a fast online interface. 

- What is the business probem that your project is trying to solve?
> Lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). The credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed.

- What is the dataset that is being used?
> Loan data for all loans issued through the time period 2007 t0 2011.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
The 5 driving factors that are strong indicators of default are:

* Interest Rate: It is observed from the analysis that applicant who have been charged higher interest rate are more likely to default.
* Annual Income : It is observed from the analysis that applicant who have lower annual income are more likely to default.
* Term : It is observed that applicant with 60 month loan term are more likely to default compare to 36 month term.
* Purpose : There is significant difference in default percentage across purpose categories, with highest value in small business.
* Subgrade : There is very high chance of default  if applicant fall under f and g categories especially f5 and g3.

So from above observation it is recommended that if any applicant fall under these criteria, bank should not give them loan directly. They should do more investigation before approving loan and thus it will reduce credit loss.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
* 1. Programming Language used – Python 3.10. 4
  2. Platform used – Jupiter Notebook v6. 4.11
  3. Libraries used:
        Numpy for Linear Algebra
        Pandas for Data Processing
        Matplotlib for Data Visualization
        Seaborn for beautiful Data Visualization

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- Developed as part of the Exloratory Data Analysis Module required for Post Graduate Diploma in Machine Learning and AI - IIIT,Bangalore.
- References if any...
- This project was based on Exloratory Data Analysis


## Contact
Created by @abhijit12banerjee and @Shubham180298


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->