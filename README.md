# A-Yen-for-the-Future

## Regression Analysis 

### The Regression Analysis notebook looks at Yen Settle prices and lagged returns over time to attempt to train a model to identify trends in a small portion of the data and use these trends to be able to predict the trend in another portion of the data it hasn't seen before. 

### This is a really cool look into a version of machine learning and being able to train a model to make predictions for the future based on what it has seen happen in the past. 

## Time Series Analysis 

### In the Time Series Analysis notebook, we take a look at the Yen prices over time and try to predict how the settle price and the volatility will be change in the future. First we look at the data and turn the data into stationary data by finding the percent change for the settle prices. Then we use a Hodrick Prescott filter to separate out the trend and the noise. 

### Next we analyzed the data using three different models: The ARMA, ARIMA, and GARCH models. The GARCH model had the best p values so it is likely the best model of the three. The GARCH model predicted a slight increase in settle price and volatility over the next five days.  