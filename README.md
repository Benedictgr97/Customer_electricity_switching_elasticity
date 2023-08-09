# Customer_electricity_switching_elasticity

## Overview
This project uses data from the .gov website, links below, to understand the movement energy customers dependent on a range of econmic factors.

The aim is to understand the  **Customer Elasticity coefficient** for a range of factors and decide which ones are the best for a quick description of customer movement 

## Methodology 
-Each metric was brought togethor at a month on month level from the .gov csv's.
-Correlations were checked to see if their were any strongly correlating groups that later on could be disgarded. Gas transfers were dropped.
-To see if there was any lag in the data the correlations of each lagged variable with transfers were displayed to see if any could be used to create a higher         -quality coefficient.
-The greatest lagged correlations where then added to the original data frame.
-The correlation and Rsquared values were then calcualated for each metric to understand the strongest descriptive factors of customer switching and how much of      -the variance each explained.
-The coefficient produced by the strongest factors are then used to determine the number of monthly customer swtiches based on these.

#
