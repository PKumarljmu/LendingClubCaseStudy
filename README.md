# Lending club case

This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface.Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'. If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.The company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.The company can utilise this knowledge for its portfolio and risk assessment. 


## Table of Contents
* Overview of the steps we are planning on EDA:
  Dataset Overview 
  Data Cleaning 
  Metrics Derivation 
  Univariate Analysis 
  Bivariate Analysis 
  Multivariate Analysis

* [Technologies Used]-Python,Numpy,Pandas

* [Conclusions]-
After all the Exploratory data analysis on the features available in the dataset, we have have arrived to the    
conclusion that the best driving features for the Loan default analysis are:
1) term, 
2) grade, 
3) purpose, 
4) revol_util, int_rate, 
5) installment, 
6) annual_inc and
7) funded_amnt_inv


<!-- You can include any other section that is pertinent to your problem -->

## General Information
- LCC is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface.Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'.

- This loan dataset has dimension as (39717, 111) including the current loan status (Current, Charged-off, Fully Paid). Loan Characteristics such as loan amount, term, purpose will help us in finding loan default. Borrower profile like age, relationship status and employment status are not relevant. Also, some of the features which are added in to the dataset after taking loans are very less significant like EMI, Delinquency, next payment date. 

- From the bar chart we can conclude that 5066 people are defaulters which is near about ~14.5 % of the total records 35152.




<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- From the bar chart we can conclude that 5066 people are defaulters which is near about 
~14.5 % of the total records 35152.

-After all the Exploratory data analysis on the features available in the dataset, we have have arrived to the conclusion that the best driving features for the Loan default analysis are below: 

1) term, 
2) grade, 
3) purpose, 
4) revol_util, int_rate, 
5) installment, 
6) annual_inc and
7) funded_amnt_inv


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used

-Python version: Python 3.9.12
-numpy version: 1.21.5
-pandas version: 1.4.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by...
- References if any...
- This project was based on [this tutorial](https://medium.com/@kg.shambhu/exploratory-data-analysis-eda-few-practical-considerations-824433ad1dfb).


## Contact
Created by [https://github.com/PKumarljmu] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->