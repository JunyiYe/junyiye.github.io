---
title: "Margin Trader LLM"
excerpt: "Adaptive and explainable margin trading via LLMs on portfolio management<br/><img src='/images/margin_trader_llm.svg'>"
collection: portfolio
---

Recent strategies for portfolio management often lack flexibility to adjust funds between long and short positions throughout trading periods, preventing portfolios from adapting to the market.

We propose an adaptive and explainable framework ([ICAIF 2024](/publication/2024-10-15-margin-trader-llm)) that integrates Large Language Models with Reinforcement Learning for dynamic long-short position adjustment in response to evolving market conditions. The framework includes an Explainable Market Forecasting/Reasoning Pipeline and a Position Reallocation stage, which interacts with a pre-trained RL model's sequential trading process to enhance decision-making and transparency. It flexibly accommodates external data sources from microeconomics to macroeconomics, diverse data types including time series and news text, and multiple LLMs. Experiments demonstrate that our framework achieves three times the return and doubles the Sharpe ratio compared to benchmarks.

Code: [github.com/JunyiYe/MarginTraderLLM](https://github.com/JunyiYe/MarginTraderLLM)
