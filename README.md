# Interactive Correlation Analyzer

### De-Risk Your Portfolio With Uncorrelated Assets

Ray Dalio states that "With fifteen to twenty good, uncorrelated return streams, you can dramatically reduce your risks without reducing your expected returns". Therefore, finding un-correlated assets (i.e., The price movement of one does not effect the other) is paramount for creating an great portfolio. After the 2020 pandemic however, correlations across sectors have increased substantialy, making uncorrelated assets difficult to find. 

Our Interactive Correlation Analyzer helps solve this problem by allowing users to visualize correlations across market sectors and time horizons and to perform risk/reward analysis on different asset combinations.


## Technologies
This project runs on python 3.7 and includes the following libraries and dependencies:

* Numpy
* Pandas 
* Matplotlib inline
* hvPlot
* Jupyter Notebook
* MCSimulations from MCForecastTools
* os
* requests
* json
* Alpaca_trade_api
* Yahoo finance api
* Seaborn
* plost
* sklearn
* datasets
* dotenv

---

## Installation Guide

To use the application you need to install the following dependencies.

```python
  pip install matplotlib
  pip install pathlib
  conda install -c anaconda requests
  conda install -c pyviz hvplot 
  pip install python-dotenv
  pip install alpaca-trade-api
  pip install altair
  pip install seaborn
  pip install streamlit
  pip install pyautogui 
  pip install plost
  
```
* Make sure to use hvPlot version 0.7.0 or later.

---

## Methodology ##

**Data Sources:**
* Y!Finance
* Alpaca API
* econDB

**Data Cleaning:**

* Finding and determining the missing values
* Finding and removing the duplicates
* Normalizing data

**Data Exploration:**

* Daily returns
* Cumulative returns
* Standard deviations
* Sharp ratio 
* Beta
* Mckenzie test
* Monte Carlo Simulation

**Data Visualization:**

* Seaborn
* Matplotlib
* Altair
* hvPlot

### Analysis Outcomes: ###

## Performance Analysis ##

![](images/line_daily_return.png)

![](images/volitility_daily_return.png)

![](images/std_volitility.png)

Bitcoin (cryptocurrency)and XLV(Healthcare) are the two most volatile sectors with high average returns are out perfoming the market.


## Correlation Analysis ##

![](images/corr.png)


![](images/correlation_heatmap.png)



* GLD (commodity) is the least correlated with all the other sectors.
* Bitcoin(cryptocurrency) ,DJP(commodity)and FXN(Energy) are also very uncorrelated.
* These sectors could be a good choice to provide cushion in the portfolio against the risk.


## Risk Analysis ##

![](images/annualized_std.png)

![](images/std_volitility.png)

Bitcoin is the highest risk asset with the maximum number of  the outliers and longer whiskers followed  by FXN(Energy Fund). This makes sense because Bitcoin has the highest standard deviation among all other sectors.


## RISK-RETURN ANALYSIS ##

![](images/sharp_ratio.png)

![](images/bar_sharp_ratio.png)

Bitcoin is having the best risk-return profile with the highest sharp ratio of 4.844 followed by QQQwhich means that from a risk-return perspective 
they offer a considerably better investment opportunity.


## DIVERSIFY THE PORTFOLIO WITH MCKENZIE TEST ##


![](images/Mckenzie_test.png)

![](images/MCK_test.png)

![](images/mckinzie_test.png)


## Montecarlo simulations ##

![](images/monte_carlo.png)

![](images/hist.png)

## Interesting Findings ##

![](images/Corr_comp.png)

After Covid-19 market became more correlated than it was before the pendemic.

## CONCLUSION: ##

* Crypto currency use to be  uncorrelated with the market but now its very correlated with the market.
* Commodity and gold sector have remained uncorrelated and may be able to contribute a good cushion in the portfolio against risk.
* Energy sector is very promising as well in terms of correlation, volatility with low risk high return profile.





## Usage

To use this application navigate to the application folder and type "streamlit run streamlit_app.py".  The application will open a new window in your default web browser AT http://localhost:8501/.  

## Dashboard

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://share.streamlit.io/dataprofessor/dashboard)




## Usage Example##

![](images/app_1.png)

![](images/app_2.png)

![](images/app_3.png)

![](images/app_4.png)

![](images/app_5.png)

![](images/app_6.png)

![](images/app_7.png)

![](images/app_8.png)

![](images/app_9.png)

**What can be improved**

* Add more functionality that will allow users to select custom sectors.

* Add more analytics tools.

* Improve interactivity with the graph.


## Contributers

Sterling Davis

David Lampach

Patrick Ball

Derick DeCesare 

Manisha Lal

(08/13/2022)

___


## License

copyright 2022
