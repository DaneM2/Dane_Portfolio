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

# [Project 2: Multiple-Regression-Project](https://github.com/DaneM2/Multiple-Regression-Project/tree/main)
## Sigma Coding Multiple Regression Project
Performed a multiple regression analysis on South Korea's GDP growth. South Korea in the 1950s came out of the Korean War, which left it's country ravaged and in extreme poverty.
However, South Korea would go through one most significant economic developments the World has seen, taking it from a country in poverty to one of the top 15 economies in the World today.
