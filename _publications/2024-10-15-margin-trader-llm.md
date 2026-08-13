---
title: "Adaptive and Explainable Margin Trading via Large Language Models on Portfolio Management"
collection: publications
category: conferences
permalink: /publication/2024-10-15-margin-trader-llm
excerpt: 'An adaptive, explainable framework combining LLMs and reinforcement learning for dynamic long-short position adjustment.'
date: 2024-10-15
venue: 'ICAIF 2024'
paperurl: 'https://doi.org/10.1145/3677052.3698681'
citation: 'Gu*, J., Ye*, J., Wang, G., &amp; Yin, W. (2024). &quot;Adaptive and Explainable Margin Trading via Large Language Models on Portfolio Management.&quot; <i>Proceedings of the 5th ACM International Conference on AI in Finance (ICAIF &#39;24)</i>, 248&ndash;256.'
---

Recent strategies for portfolio management often lack flexibility to adjust funds between long and short positions throughout trading periods, preventing portfolios from adapting to the market. To address these gaps, we propose an adaptive and explainable framework that integrates Large Language Models (LLMs) with Reinforcement Learning (RL) for dynamic long-short position adjustment in response to evolving market conditions. The framework includes two stages: an Explainable Market Forecasting/Reasoning Pipeline, and a Position Reallocation stage. The Market Forecasting/Reasoning Pipeline allows various LLMs to learn market trends from diverse external data sources and determine optimal adjustment ratios with a clear reasoning path. The Portfolio Reallocation stage interacts with the sequential trading process from a pre-trained RL model to enhance decision-making and transparency. Experiments demonstrate that our framework achieves three times the return and doubles the Sharpe ratio compared to benchmarks.

Code: [github.com/JunyiYe/MarginTraderLLM](https://github.com/JunyiYe/MarginTraderLLM)
