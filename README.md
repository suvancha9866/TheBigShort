# TheBigShort
This is our github for our Fall 2023 Data Dive project where we take a look at historical rates of different banks and compare them to the National rates to try and predict future collapses based on the 2008 Recession.


Our NewInterestRateData file contains columns for federal fund rates like the APR, FFR, and SPX(though in the sense that much of the financial world revolves around the S&P 500). We also have yearly stock averages for 8 banks to have a baseline. To best predict future collapses, two factors we chose were the Interest on Deposit and Loan on Default for each company. These two factors for each bank were what we thought would be the best way to help predict future collapses. 


We took 8 small/mid cap banks in the industry because these are the banks that wouldn't be hleped by the government and survived on their own. Otherwise these banks would've collapsed in the 2008 recession or not have been founded. These were a variety of banks that we thought would be good to choose so we decided on them.


We took factors like the IOD and the NII of each bank as predictors for a loan default. We thought that these would be the best ways to predict a loan default amount of a bank. Using how well correlated each bank was to each factor, we used those specific pieces to create predictions for years.


Either the factors were negatively or positively correlated with each factor so we took the strongest negative or positive correlations and then ran a linear regression on the factors as predictors and the loan default being the outcome.

There are some important factors to look at one of them is that the 

FFR - The overnight rates bank charge with each other to keep their reserves. Banks also have to keep their reserves at the federal reserves account, for safety purposes.

BPS- Bassis points 1 basis point is 0.01%

NII - Net interest income, the income banks earn from their interest after direct expenses

Loan Default - We took the amount where the loans have not been paid for more than 90 days.

APR - Interest charged on a loan on an annaluized term.

History

The Federal Reserve is the central bank of the United States and is responsible for maintaing the cost of money. It as a dual mandate keeping unemployment and inflation stable. The Federal Reserve was created after the banking crisis in 1907 where banks collapsed because of no authority to keep trust of people. The Federal Reserve works seperately from the other governments and is reponsible for maintaining the money supply. It is referred to as the M2 Money supply.

Recent Events

It is important to understand liquidity to understand our project. In the past it took lesser hikes to affect the banks We found that when we did correlation testing we pre 2008 there was a strong correlation with interest payments on loans compared to post 2008. As post 2008 what happened was the federal reserve printed record amount of money, there was high liqudiity in the markets and many borrowers locked in fixed rates compared to variable rates. These factors played a role in a weak correlation post 2008 between interest on loans and interest rates hike.
