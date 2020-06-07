# High Frequency Finance

## Data Sources
- TickData is an expensive but comprehensive place to get all ticks data
- iqfeed provides reasonable price for the following data:
  - 180 calendar days of tick history (includes pre-post market) with microsecond timestamps (if available from the exchange feed)
  - 11+ years of 1-Minute OHLCV historical data on exchanges/data authorized depending upon instrument and when we started collecting data.***
    - Forex back to February 2005
    - Eminis back to September 2005
    - US Stock/Futures/Indexes back to May 2007
    - London Stocks and FTSE Indexes back to February 2016 

  - Up to 80+ years of Daily, Weekly and Monthly OHLCVOI Historical data depending upon instrument and when we started collecting data.
    - Indexes as far back as 1929
    - US Stocks as far back as 1994
    - Forex as far back as 1993
    - US Futures as far back as 1959
    - London Stocks and FTSE Indexes as far back as 1985 

## Econometrics
- Aït-Sahalia and Jacod, High Frequency Econometrics: https://muse.jhu.edu/book/41675
  - Its second chapter discusses data issues involved with high frequency data
- Dacheng Xiu, Jia Li are the scholars to follow

# References
[AX2017]: Yacine Aït-Sahalia, Dacheng Xiu, Using principal component analysis to estimate a high dimensional factor model with high-frequency data,
Journal of Econometrics, Volume 201, Issue 2,2017, https://www.sciencedirect.com/science/article/pii/S0304407617301677?via%3Dihub
[AFL2013]: Yacine Aït-Sahaliaa, Jianqing Fan, Yingying Li , The leverage effect puzzle: Disentangling sources of bias at high frequency
## TODo
- [ ] Momentum Crashes by Moskowitz

