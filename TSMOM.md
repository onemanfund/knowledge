# Time Series Momentum (TSMOM)

## What is TSMOM

TSMOM says that if an asset has been appreciating (depreciating) *recently* against *itself* then we should long (short) it to get rewarded. Deceptively simple. There are many details we need to flesh out:

1. How to operationalize the idea of "recently appreciating"?
2. How big the allocation should once we determine the asset has momentum?
3. How do we diversify across assets?

To answer these questions, let's do a guided literature review. This literature review is based on the book Efficiently Inefficiency by Lasse Pedersen and a series of blog posts by [Alpha Architect](https://alphaarchitect.com). Obviously we add our own research.

## Existing Research

The seminal contribbution is [MOP2012](https://cyberleninka.org/article/n/1285206.pdf) where they first gather evidence for existence of large and consistent reward for trend-following. Later a follow up piece with longer history and more country coverage is published [HOP2017]. The key features of MOP approach are:

1. They scale recent return by an estimate of recent volatility in the stage of portfolio construction
2. Their regression analysis is done via pooling all assets (future contracts of different assets)

Naturally, scholars debate. [ATW2016] attributes much of the alhpa to volatility scaling, 

## Data Sources
- AQR publishes monthly TSMOM return [here](https://www.aqr.com/Insights/Datasets/Time-Series-Momentum-Factors-Monthly)


# References

[MOP2012]:  Moskowitz, Tobias J., Yao Hua Ooi, and Lasse Heje Pedersen. "Time series momentum." Journal of financial economics 104.2 (2012): 228-250.

[HOP2017]: Hurst, Brian and Ooi, Yao Hua and Pedersen, Lasse Heje, A Century of Evidence on Trend-Following Investing (June 27, 2017). Available at SSRN: https://ssrn.com/abstract=2993026 or http://dx.doi.org/10.2139/ssrn.2993026 

[ATW2016]: Kim, Abby Y., Yiuman Tse, and John K. Wald. "Time series momentum and volatility scaling." Journal of Financial Markets 30 (2016): 103-124.


TODO:
[ ] Momentum Crashes by Moskowtiz
[ ] Read that deep neural network paper https://arxiv.org/pdf/1904.04912.pdf
