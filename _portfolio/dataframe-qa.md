---
title: "DataFrame QA"
excerpt: "A universal LLM framework on DataFrame question answering without data exposure<br/><img src='/images/dataframe_qa.svg'>"
collection: portfolio
---

This project introduces DataFrame Question Answering (QA), a novel task that utilizes NLP models to generate Pandas queries for information retrieval and data analysis on dataframes, emphasizing safe and non-revealing data handling.

**DataFrame QA** ([ACML 2024](/publication/2024-09-05-dataframe-qa)) leverages an LLM that solely relies on dataframe column names, ensuring data privacy while significantly reducing the context window in the prompt. Our comprehensive framework includes safe Pandas query generation and code execution, evaluated on the renowned WikiSQL dataset and our newly developed UCI-DataFrameQA. GPT-4 performs well on both datasets, underscoring its capability in securely retrieving and aggregating dataframe values and conducting sophisticated data analyses in a zero-shot manner.

Code: [github.com/JunyiYe/dataframe-qa](https://github.com/JunyiYe/dataframe-qa)
