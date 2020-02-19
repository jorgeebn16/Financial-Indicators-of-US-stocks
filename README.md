# Financial-Indicators-of-US-stocks
Financial Indicators of US stocks. Try to predict stocks' future performance leveraging 200+ financial indicators

Companies have spent billions in infrastructures and R&D to be able to jump ahead of the competition and beat the market. Still, it is well acknowledged that the buy & hold strategy is able to outperform many of the algorithmic strategies, especially in the long-run. However, finding value in stocks is an art that very few mastered, can a computer do that?

Content
This Data repo contains the following datasets (in .csv format):

2014_Financial_Data.csv
2015_Financial_Data.csv
2016_Financial_Data.csv
2017_Financial_Data.csv
2018_Financial_Data.csv

This dataset (.csv) collects 200+ financial indicators for all the stocks of the US stock market. The financial indicators have been scraped from Financial Modeling Prep API, and are those found in the 10-K filings that publicly traded companies release yearly.

The last column of the dataset represent the class of each stock, where:

if the value of a stock increases the next year, then class=1;
if the value of a stock decreases the next year, then class=0.
In other words, stocks that belong to class 1 are stocks that one should buy at the start of the next year, and sell at the end of year.

This dataset has been developed in order to understand whether or not it is possible to classify the future performance of a stock by looking at the financial information released in the 10-K filings.

Is it possible to answer a simple question: is it possible to have a machine learning model learn the differences between stocks that perform well and those that don't, and then leverage this knowledge in order to predict which stock will be worth buying? Moreover, is it possible to achieve this simply by looking at financial indicators found in the 10-K filings?
