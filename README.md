# Lending Club Case Study
> Lending Club is consumer finance company which specializes in lending various type of loan. 
When company receives a loan application, it decides to accept or reject the loan based on applicant's profile. 
Once loan is approved, there are two possibilities, either the applicant will repay the full loan amount or he will default on the loan amount. 
The past loan applicantion data is available on whether they defaulted or not. The company wants to understand the driving factors behind loan default.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
- This project performs exploratory data analysis on the loan details available from lending club and identifies the important factors causing the loan borrowers to default on loan.
It shows some important visual insights of the correlation of loan status with different loan features.


## Conclusions
- Borrowers taking loan for 60 months tenure have the higher default rate compared to borrowers taking loan for 36 months.
- Borrowers in grade F and G has highest default rate.
- Borrowers in subgrade F5 and G3 has highest default rate.
- Loan taken for small business purpose has the highest default rate.
- Default rate increases with increase in loan amount and interest rate.
- Default rate increases with decrease in annual income.
- Borrowers from state "NE" have highest default rate.
- Borrowers belonging to these zip codes has more than 50% default rate - 094xx,373xx,385xx,561xx,663xx,669xx,685xx,689xx,746xx,833xx,999xx
- Borrowers belonging to grade G and who has taken loan for 36 months tenure has highest default rate.
- Borrowers who have taken loan for 36 months term and belongs to subgrade G3 has 100% default rate and who belongs to G5 has 60% default rate.
- Loan taken for Small Business and Education have the highest default rate for loan term of 60 months.
- Loan taken with interest rate higher than 16.83% has highest default rate for 60 months loan term.
- Loan taken by Grade G for renewal energy purpose has 100 % default rate and for medical purpose has around 67% default rate.
- These combination of subgrade and purpose of loan has 100% default rate
		Purpose	                   SubGrade
		Car	                       G3
		house	                   F2,F4
		medical	                   F3,G1
		moving	                   F5
		renewal energy	           F1,G4,G5
		wedding	                   G2
- Loan taken with interest rate higher than 16.83% has highest deafult rate if loan is take for renewal enery, small business, house, medical and car purpose.
- Borrowers with grade D,E,F and G has very high default rate for loan taken with interest rate higher than 16.83%. 
- Borrowers with grade F has the highest default rate even for loan taken with interest rate greater than 11% and less than 16.83%.


## Technologies Used
- pandas - version 1.2.4
- numpy - version 1.20.1
- matplotlib - version 3.3.4
- seaborn - version 0.11.1


## Acknowledgements

- References
	https://www.kaggle.com/ekami66/detailed-exploratory-data-analysis-with-python.

## Contact
Created by [@saketbihari] - feel free to contact me!


