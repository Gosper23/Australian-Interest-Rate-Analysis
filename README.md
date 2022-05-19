## The purpose of this work is to idenfiy how in Australia, interest rate change will effect on:

* Inflation, GDP, or unemployment

* Stock indexes

* Currency Exchange rates


## Questions 1

Will change of Interest Rate effect Inflation, GDP, or unemployment?

### Major findings:

No obvious trend detected on GDP and Inflation, however soome interesting findings on correlation between interest rate and unemployment rate.

During year 2008-2011, when interest rate raise, unemployment goes down and vice versa

Interest rate seems to be significantly negatively correlated with unemployment rate.

![inflation](https://github.com/Gosper23/Australian-Interest-Rate-Analysis/blob/features_jm/Images/Financial%20Factors.png)

## Question two:

Will Interest rate effect the index of the 11 sectors of on ASX exchange?

### Major findings:

11 sectors are Energy, Materials, Industrials, Consumer Discretionary, Consumer Staples, Health Care, Financials, Information Technology, Communication Services, Utilities and Real Estate. 
From the data anylyais it is found that the interest rate rise and fall was closest correlated with Materials

![inflation](https://github.com/Gosper23/Australian-Interest-Rate-Analysis/blob/features_jm/Images/ASX.png)

## Question three:

Will Interest Rate effect currency exchange rates ? (USD, EUR, GBP, CAD, NZD, SGD)

### Major findings:

Some instances when rates fall, currency falls and vice versa,but no obvovious high correlation against the iterest rate changes.


![inflation](https://github.com/Gosper23/Australian-Interest-Rate-Analysis/blob/features_jm/Images/Currency%20Graph.png)


## The work contains:

Comparison on Interest Rate vs Inflation, GDP, unemployment:

* isolate range of 2000-6 to current, sorting, drop null, drop %, setting index, 

* using panda's libaray to concat dataframe on actualfigure and percentage change, using hvplot and bokeh to graph the final result

Comparison on Interest Rate vs Stock indexes in the 11 sectors of the ASX exchange:

* check and drop nulls, set date column as object, convert object data in data frames to numeric.
create date column.

* concat to produce two data frames, one actual value of closing and one on percentage change

* plot data frame on percentage change into heatmap. created line graph.



Comparison on Interest Rate vs Currency Exchange rates ( USD, GBP,  EUR, CAD, NZD, SGD): 

* imported csv files, drop irrelevant columns, check null, drop null value setting index for USD, concat dataframe.
export clean data.

* merge dataframe of interst rates and currenies. group currency data by montly average.

* plot correlation matrix on percentage change.  


Libary used: os, Path, dotenv, datetime, pandas, numpy, holoviews, bokeh, seaborn,panel,plotly,hvplot

Data source: refinitiv - Finance Software, [abs](https://www.abs.gov.au) 
 [investing.com](https://au.investing.com/) 
