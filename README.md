# Personal Saving Rate (PSAVERT)
__A descriptive analysis of the Personal Saving Rate (PSAVERT) from 1959 to 2014 as reported by FRB St. Louis.__

##About Project
R version 3.1.2 (2014-10-31) "Pumpkin Helmet" of the R programming language and software environment for statistical computing and graphics was utilised to calculate and generate the data.

The personal saving is calculated as a percentage of disposable personal income (DPI), frequently referred to as “the personal saving rate". It is calculated as the ratio of personal saving to DPI. Data is reported monthly and represents the seasonally adjusted Annual Rate provided by the US. Bureau of Economic Analysis.

##Procedure
###Raw Data
The raw data used for this project is located [here](https://github.com/nickhepler/psavert/blob/master/_data/PSAVERT.csv).
The data was originally retrieved from the Federal Reserve Economic Data (FRED) Economic Data maintained by the Federal Reserve Bank of St. Louis. The following parameter selection was used:
*   Units: Percent
*   Frequency: Monthly
*	  Date Range: 1959-01-01 to 2014-11-01
*	  File Format: Text, Comma Seperated
The data was retrieved on December 28, 2014.

Data Sheet
See https://github.com/nickhepler/datasharing

## Source
US. Bureau of Economic Analysis, Personal Saving Rate [PSAVERT], retrieved from FRED, Federal Reserve Bank of St. Louis https://research.stlouisfed.org/fred2/series/PSAVERT/, December 28, 2014.

##Changelog
_2015-01-24  Nick Hepler  <nick.hepler@outlook.com>_
*   Initial commit
