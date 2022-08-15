# Prosper Loan Data Exploration

## Introduction
This analytics is focused on generating insights from the Prosper loan dataset to understand factors that affect loan amount.

## Practices
1. Assess and wrangle the dataset
2. Explore the dataset using appropriate plots to present findings.
3. Create Univariate, Bivariate and Multivariate plots to get understanding of data.


## Libraries and Packages used
The libraries used in this project are as follows:
1. NumPy
2. Pandas
3. Matplotlib
4. Seaborn


## Dataset

This document explores a dataset of 84672 rows and 23 columns of loan data. It is worthy to note that this is a subset of the original dataset which contains 113937 entries, 81 columns. 

The original dataset can be found [here](https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv), with data dictionary [here](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0)


## Data Wrangling
1. A sample of the original dataset was used.
2. Feature Engineering and data transformation was done.
3. Dataframe was assessed programmatically and visibly for Data Quality and Tidiness Issues.
4. Sample dataset was stored and used for exploratory and explanatory dataset.



## Summary of Findings
Based on the explotation of the clean dataset, I have explored some features of interest.

- Borrowers with higher monthly income got the highest loan amounts with most of them between 25,000 and 75,000.

- Loans made for `36 months` tend to have the highest users and even the highest loan amounts.

- Borrowers who were home owners had a higher borrower rate and borrower APR.


## Limitations

The sad occurrence of multiple null values across some important features limits diverse explorations.



## Key Insights 
For the presentation, I focus on the influence of the Borrowers Income range, Stated Monthly Income, Monthly Loan Payment and Loan term, and information on whether they are home owners or not on Loan Amount. 
    These explorations show that borrowers who own their homes, take a higher loan, have higher income and remit higher monthly payment. They also have the best scores and ratings.

I used scatter plots showing the correlation between Loan Amount and Stated Monthly income. When the borrower’s Monthly Income is high, he/she is more likely to get a Large Loan Amount.
