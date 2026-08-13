---
title: "Prediction with Time-Series Mixer for the S&P500 Index"
collection: publications
category: conferences
permalink: /publication/2023-01-01-time-series-mixer
excerpt: 'A Time-Series Mixer (TS-Mixer) architecture, based on MLP-Mixer, for multivariate time series forecasting applied to S&P500 Index prediction.'
date: 2023-01-01
authors: "Junyi Ye, Jingyi Gu, Ankan Dash, Fadi P. Deek, Guiling Grace Wang"
venue: '2023 IEEE 39th International Conference on Data Engineering Workshops (ICDEW), 20–27'
citation: 'Ye, J., Gu, J., Dash, A., Deek, F. P., &amp; Wang, G. (2023). &quot;Prediction with Time-Series Mixer for the S&amp;P500 Index.&quot; <i>2023 IEEE 39th International Conference on Data Engineering Workshops (ICDEW)</i>, 20&ndash;27.'
---

As an essential US economic indicator, the S&P500 Index is used to assess the current state of market performance and gauge the economy's future course. However, stock market index prediction is challenging due to its nonlinearity and inherently volatile character. Recurrent Neural Networks (RNNs) and their variants are de facto standards for sequence modeling; more recently, Convolutional Neural Networks and attention-based networks, such as dilated causal convolutions and Transformers, have also become popular in time series forecasting. In this paper, we report on the design of a **Time-Series Mixer (TS-Mixer)** architecture based on MLP-Mixer, an all-MLP architecture for time series forecasting — to our knowledge, the first implementation of an MLP-Mixer-based architecture for sequence modeling. The proposed architecture is specifically created for multivariate time series forecasting, using a feature mixer to capture correlations among features and a temporal mixer to extract temporal dependencies. Compared to prevalent neural networks in sequence modeling, TS-Mixer exhibits competitive performance on S&P500 Index prediction.
