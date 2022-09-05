# WeRateDogs Tweets Analysis

# Author
Built by : Kelvin Njuguna Kimani


# Description

> The Loan data from prosper contains a total of 113,937 loan records, each with a total of 81 variables. Due to the bulk nature of the dataset, for this Exploratory exercise, only 15 loan variables will be considered. they include:
>> 1. **Term:** The length of the loan expressed in months.
>> 2. **ProsperScore:** A custom risk score built using historical Prosper data. The score ranges from 1-10, with 10 being the best, or lowest risk score.  Applicable for loans originated after July 2009.
>> 3. **BorrowerState:** The two letter abbreviation of the state of the address of the borrower at the time the Listing was created.
>> 4. **Occupation:** The Occupation selected by the Borrower at the time they created the listing.
>> 5. **EmploymentStatus:** The employment status of the borrower at the time they posted the listing.
>> 6. **EmploymentStatusDuration:** The length in months of the employment status at the time the listing was created.
>> 7. **IsBorrowerHomeowner:** A Borrower will be classified as a homowner if they have a mortgage on their credit profile or provide documentation confirming they are a homeowner.
>> 8. **CreditScoreMid_range:** The arithmetic mean of the `CreditScoreRangeLower` and `CreditScoreRangeUpper`
>> 9. **DelinquenciesLast7Years:** Number of delinquencies in the past 7 years at the time the credit profile was pulled.
>> 10. **StatedMonthlyIncome:** The monthly income the borrower stated at the time the listing was created.
>> 11. **LoanOriginalAmount:** The origination amount of the loan.
>> 12. **MonthlyLoanPayment:** The scheduled monthly loan payment.
>> 13. **LP_CustomerPayments:** Pre charge-off cumulative gross payments made by the borrower on the loan. If the loan has charged off, this value will exclude any recoveries.
>> 14. **LP_InterestandFees:** Pre charge-off cumulative interest and fees paid by the borrower. If the loan has charged off, this value will exclude any recoveries. 

> The cleaned data consisted of Loan borrower information of 83,507 loan borrowers, with each entry having 15 attributes. 

#
# Prerequisites
- Conda environment
- pip
- python 3
- jupyter notebook
#

# Cloning
Open Terminal and run the commands below:

- `git clone https://github.com/Kevson1/Loan-Data-Analysis`
#
# Running the Notebook
After cloning the repository, run the commands below:
- `cd Twitter-archive`
- `conda env create -f environment.yaml` (For the conda environment)
- `pip install -r requirements.txt` (For the pip environment)
- `conda activate loans`
- `jupyter notebook`

This should open the `jupyter notebook` in the browser. Click on the respective notebook file to open.