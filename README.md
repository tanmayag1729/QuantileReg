# Time Series Quantile Regression
In this project, the following research paper has been implemented: http://www.economics-ejournal.org/economics/journalarticles/2019-26/ and a simple trading strategy has been created based on the same.

The dataset for the same is availabe at: http://dx.doi.org/10.7910/DVN/MCOVPQ

This paper utilizes quantile regression (an extension of linear regression) to predict the future return of the KOSPI 200 index based on the lag - 1,2,3 returns and volume. Quantile regression provides us with a distribution of returns rather than the mean future return (which is 0 in most cases) that linear regression provides.
Linear regression "fits" the mean of each independent variable to the dependent variable whereas quantile regression can fit any percentile of the independent variable to the percentile of the dependent variable. 

In the first notebook, the research paper has been implemented and effort has been made to replicate the results of the paper.
In the second notebook, a simple trading strategy has been created based on the future returns predicted using Quantile regression.
