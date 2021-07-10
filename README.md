# Dane_Portfolio
Data Analytics | Data Science portfolio

# [Project 1: Web-Traffic-Forecasting---Capstone](https://github.com/DaneM2/Web-Traffic-Forecasting---Capstone)
This project looks at the problem of forecasting future values of time-series data. Wikipedia has over 145,000 articles and their view counts available to analyze. Following the Exploratory Data Analysis (EDA) process I was able to develop an Auto-Regressive Integrated Moving Average (ARIMA) model that showed a prediction of view counts for the following 45 – 60 days. Web forecasting is gaining popularity and has many applications including load balancing for cloud services, and understanding user behavior.

## What is Web Traffic Forecasting?
* Predict web traffic trends based on historic data
* Develop strategies for Load balancing applications
* Better understand user behavior

## Potential Customers
 Businesses looking for insights on web traffic to improve efficiency and gain a competitive edge\
 Forecasting is ubiquitous across industries:
 * Operations
 * Retail
 * Marketing
 * Logistics

# Exploratory Data Analysis (EDA)
### Software:
**R with Rstudio:** tidyverse, plotly, forecast, prophet, ggplot2, dplyr

## Data source:
Source: https://www.kaggle.com/c/web-traffic-time-series-forecasting/data \
Approximatley 145,000 time series:
* Daily page views, 2015-07-01 to 2016-12-31

![](images/data.PNG)

## Cleaning and Transformation
* Checked for missing values using is.na 
* Seperated the date and pages to seperate tibbles for visualization
* Renamed and restructured page values to be easier to work with

![](images/cleaned%20data.PNG)

### Time-series Extraction
![](images/Timeseries%20WIKI.png)

![](images/TImeseries%20avg%20traffic%20WIKI.png)

## The Variables:
* locale data includes 7 languages: German, English, Spanish, French, Japanese, Russian, and Chinese
* Access: Platform used to view page
* Agent being a real person and spider being a bot used to index content

![](images/Variables.png)

## Understanding Trends
### Looking for any trends in the distribution
* Broken down by min, max, mean, median, standard deviation, and slope

![](images/Trends.PNG)

## Outliers
Clear examples of outliers. Zero views for all dates, spikes to over 10^6

![](images/Outliers.png)

## Model Selection - Arima
### Stands for Auto Regressive Integrated Moving Average
* **ARIMA** has 3 terms AR, I, and MA
* (AR) corresponds to Lags of the stationarized series
* (MA) corresponds to lags of the forecast error
* (I) corresponds to order of differencing of series to make it stationary
* Captures complex relationships through an iterative process of regressing a variable: Views ~ Dates\

*AR Model*: This model forecasts future values based on the immediate prior value in the time-series\
*MA Model*: equal to the past error multiplied by the coefficient

## Auto.Arima Results
### Prediction Length of 45 Days

![](images/Auto_Arima.png)

## Residuals
* Strong p-value = 0 .017 (less than 0.05)
* Residuals are normally distributed
* Mostly absent of autocorrelation 
*
![](images/Ljung-box%20test.png)

## Prophet Model

## Improvements

## References

# [Project 2: Multiple-Regression-Project](https://github.com/DaneM2/Multiple-Regression-Project/tree/main)
## Sigma Coding Multiple Regression Project
Performed a multiple regression analysis on South Korea's GDP growth. South Korea in the 1950s came out of the Korean War, which left it's country ravaged and in extreme poverty.
However, South Korea would go through one most significant economic developments the World has seen, taking it from a country in poverty to one of the top 15 economies in the World today.
