# TheBigShort
This is our github for our Fall 2023 Data Dive project where we take a look at historical rates of different banks and compare them to the National rates to try and predict future collapses based on the 2008 Recession.


Our NewInterestRateData file contains columns for federal fund rates like the APR, FFR, and SPX(though in the sense that much of the financial world revolves around the S&P 500). We also have yearly stock averages for 8 banks to have a baseline. To best predict future collapses, two factors we chose were the Interest on Deposit and Loan on Default for each company. These two factors for each bank were what we thought would be the best way to help predict future collapses. 


We took 8 small/mid cap banks in the industry because these are the banks that wouldn't be hleped by the government and survived on their own. Otherwise these banks would've collapsed in the 2008 recession or not have been founded. These were a variety of banks that we thought would be good to choose so we decided on them.


We took factors like the IOD and the NII of each bank as predictors for a loan default. We thought that these would be the best ways to predict a loan default amount of a bank. Using how well correlated each bank was to each factor, we used those specific pieces to create predictions for years.


Either the factors were negatively or positively correlated with each factor so we took the strongest negative or positive correlations and then ran a linear regression on the factors as predictors and the loan default being the outcome.