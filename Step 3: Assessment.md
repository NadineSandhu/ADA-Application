# ADA-Application
Phase 1 Ada Application for Nadine Sandhu
##Step 3: Assessment

###Question 1
Please provide your answer as a number. Consider all of the schools that disbursed a total of more than $25,000,000 in loans during a single quarter. How many more schools met this criteria in 2015 than in 2010?

###A:40

####Process:
1) Sorted data by School Type column and deleted all Foreign institutions per instruction
2) Insterted column to the right of the Zip Code column, and added the _=right(D3,1)_ formula
3) Sorted data by _=right(D3,1)_ formula and deleted all rows with numbers 3,5,7 per instruction
4) Added column to the right of column B titled "Cumulative Total Disbursments" and added _=sum(...,...) for all $ of Disbursments cells
5) Copied formula down entire spreadsheet
6) Sorted data by "Cumulative Total Disbursments" descending
7) Scrolled to cell with $25,000,000 in loans and calculated the total - 2 for top two header rows.
8) Repeated steps 1 through 7 with 2015/16 spreadsheet

2010/11 = 225

2015/16 = 185

###Question 2
Please provide your answer as a number. For each state calculate the number of recipients for undergraduate student loans at non-public institutions in 2015. What was the largest difference between subsidized and unsubsidized loans in a single state?

###A:

AK:
