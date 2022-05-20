## Purpose of this work is to idenfiy, in Australia, how interest rate change effect on:

* Inflation, GDP, or unemployment rate

* Stock indexes

* Currency Exchange rates


### Major Question one:

Will change of Interest Rate effect Inflation, GDP, or unemployment rate?

### Findings:

No obvious trend detected on GDP and Inflation. However, some interesting findings on correlation between interest rate and unemployment rate.

During year 2008-2011, when interest rate raise, unemployment goes down and vice versa

Interest rate seems to be significantly negatively correlated with unemployment rate.

![inflation](https://github.com/Gosper23/Australian-Interest-Rate-Analysis/blob/features_jm/Images/Financial%20Factors.png)

### Major Question two:

Will Interest rate effect the index of the 11 sectors on the ASX exchange?

### Findings:

The 11 sectors on the ASX exchange are Energy, Materials, Industrials, Consumer Discretionary, Consumer Staples, Health Care, Financials, Information Technology, Communication Services, Utilities and Real Estate. 
From the data anylyais, it is found that the interest rate rise and fall was somehow closest correlated with Materials

![inflation](https://github.com/Gosper23/Australian-Interest-Rate-Analysis/blob/features_jm/Images/ASX.png)

### Major Question three:

Will Interest Rate effect currency exchange rates ? (USD, EUR, GBP, CAD, NZD, SGD)

### Findings:

Some instances when rates fall, currency falls and vice versa,but no obvovious high correlation against the iterest rate changes.


![inflation](https://github.com/Gosper23/Australian-Interest-Rate-Analysis/blob/features_jm/Images/Currency%20Graph.png)


## This repo contains:

Comparison on Interest Rate vs Inflation, GDP and Unemployment:

* Isolate range of 2006 to current, sorting, drop null, drop %, setting index, 

* Using panda's libaray to concat dataframe on actualfigure and percentage change, using hvplot and bokeh to graph the final result

Comparison on Interest Rate vs Stock indexes in the 11 sectors of the ASX exchange:

* Check and drop nulls, set date column as object, convert object data in data frames to numeric.
create date column.

* Concat to produce two data frames, one actual value of closing and one on percentage change

* Plot data frame on percentage change into heatmap. create line graph.



Comparison on Interest Rate vs Currency Exchange rates ( USD, GBP,  EUR, CAD, NZD, SGD): 

* Import csv files, drop irrelevant columns, check null, drop null value setting index for USD, concat dataframe.
export clean data.

* Merge dataframe of interst rates and currenies. group currency data by montly average.

* Plot correlation matrix on percentage change.  


Libaries used: os, Path, dotenv, datetime, pandas, numpy, holoviews, pandas_bokeh,panel, plotly,hvplot

##Data source: 
refinitiv - Finance Software, 

[abs](https://www.abs.gov.au) 

[investing.com](https://au.investing.com/) 

Find our presentation [here](https://docs.google.com/presentation/d/1O1nfnlkPutPFFq8dUQorQkbq9JduA0Up/edit?usp=sharing&ouid=117874016718866142052&rtpof=true&sd=true) 
