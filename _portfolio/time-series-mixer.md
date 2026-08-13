---
title: "Time-Series Mixer"
excerpt: "Prediction with time-series mixer for the S&P500 index<br/><img src='/images/ts_mixer.svg'>"
collection: portfolio
---

As an essential US economic indicator, the S&P500 Index is used to assess current market performance and gauge the economy's future course. However, stock market index prediction is challenging due to its nonlinearity and inherently volatile character. Recurrent Neural Networks and their variants are the de facto standard for sequence modeling, while Convolutional and attention-based networks have also become popular in time series forecasting.

We report on the design of a **Time-Series Mixer (TS-Mixer)** ([ICDEW 2023](/publication/2023-01-01-time-series-mixer)) architecture based on MLP-Mixer, an all-MLP architecture for time series forecasting — to our knowledge, the first implementation of an MLP-Mixer-based architecture for sequence modeling. The architecture is specifically designed for multivariate time series forecasting: a feature mixer captures correlations among features, while a temporal mixer extracts temporal dependencies (trend, seasonal, cyclical, or random characteristics). Compared to prevalent neural networks in sequence modeling, TS-Mixer exhibits competitive performance on S&P500 Index prediction.
