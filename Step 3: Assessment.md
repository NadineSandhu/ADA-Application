# ADA-Application
Phase 1 Ada Application for Nadine Sandhu
##Step 3: Assessment

###Question 1
Please provide your answer as a number. Consider all of the schools that disbursed a total of more than $25,000,000 in loans during a single quarter. How many more schools met this criteria in 2015 than in 2010?

###A: -40

2010/11 = 225

2015/16 = 185

####Process:
1) Sorted data by School Type column and deleted all Foreign institutions per instruction

2) Inserted column to the right of the Zip Code column, and added =right(D3,1) formula

3) Sorted data by =right(D3,1) column and deleted all rows with numbers 3,5,7 per instruction

4) Added column to the right of column B titled "Cumulative Total Disbursements" and added _=sum(...,...) for all $ of Disbursements cells

5) Copied formula down entire column on spreadsheet

6) Sorted data by "Cumulative Total Disbursements" descending

7) Scrolled to cell with $25,000,000 in loans and calculated the total minus 2 for top two header rows

8) Repeated steps 1 through 7 with 2015/16 spreadsheet

9) Took total from 2010/11 spreadsheet of 225 and subtracted total from 2015/16 spreadsheet of 185

10) 225 - 185 = 40

11) Answer: 40 more schools met the 25M disbursement quota in 2010/11 vs. 2015/16

###Question 2
Please provide your answer as a number. For each state calculate the number of recipients for undergraduate student loans at non-public institutions in 2015. What was the largest difference between subsidized and unsubsidized loans in a single state?

###A: 100% subsidized (Wyoming)

Of Wyoming's 117 Undergraduate loans given out, 100% were subsidized. This was the largest margin when compared to other States between subsidized and unsubsidiezed loans.

####Process:
1) Sorted spreadsheet by School Type and removed all rows listing "Public" per instructions

2) Sorted spreadsheet by "State" column

3) Insterted row between each state

4) Created =sum(range:) formula to calculate total for entier state for subsidized and unsubsidized loans

5) Inserted column and calculated % based on total of subsidized vs. unsubsidiez loans per state

*Example: Alaska
    Total Recipients: 140 (sub 77, un 63)
    77/140=55%
    63/140=45%

###QUESTION 3
Compare HBCUs established prior to the Reconstruction Era and those established during Reconstruction. Which group had the largest change in number of loan recipients between 2010 and 2015?

###A: During the Reconstruction Era

####Process:
1) Reconstruction Era spanned from 1865-1877.

2) Searched online and found list of HBCU on wikipedia

3) Compiled all HBCU's which met the above criteria

4) Calculated total loan recipients for each column

5) Calculated % change (decrease = new number - old number, decrease/new number*100 = %)

####Prior to Reconstruction Era (1864)

    2010/11= 7,028

    2015/16 = 6,860

    **_-168 or -2.39% decrease_**

####During Reconstruction Era (1865-1877)

    2010/11 = 91,128

    2015/16 = 78,149

    **_-12,979 or -14.24% decrease_**

*Disclaimer. Some HBCU's from wikipedia did not appear on the spreadsheet. I have assumed this is due to the zip code exclusions. 

Example:
Harris-Stowe State University College, zip code ended in 3
