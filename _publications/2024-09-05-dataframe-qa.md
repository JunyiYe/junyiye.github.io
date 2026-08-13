---
title: "DataFrame QA: A Universal LLM Framework on DataFrame Question Answering Without Data Exposure"
collection: publications
category: conferences
permalink: /publication/2024-09-05-dataframe-qa
excerpt: 'A universal LLM framework for DataFrame question answering that relies only on column names, preserving data privacy.'
date: 2024-09-05
venue: 'ACML 2024 (Conference Track)'
paperurl: 'https://openreview.net/forum?id=rDNj0enuhc'
citation: 'Ye, J., Du, M., &amp; Wang, G. (2024). &quot;DataFrame QA: A Universal LLM Framework on DataFrame Question Answering Without Data Exposure.&quot; <i>The 16th Asian Conference on Machine Learning</i>.'
---

This paper introduces DataFrame Question Answering (QA), a novel task that utilizes natural language processing (NLP) models to generate Pandas queries for information retrieval and data analysis on dataframes, emphasizing safe and non-revealing data handling. Specifically, our method, leveraging a large language model (LLM) that solely relies on dataframe column names, not only ensures data privacy but also significantly reduces the context window in the prompt, streamlining information processing. We propose DataFrame QA as a comprehensive framework that includes safe Pandas query generation and code execution. Various LLMs are evaluated on the WikiSQL dataset and our newly developed UCI-DataFrameQA. Our findings indicate that GPT-4 performs well on both datasets, underscoring its capability in securely retrieving and aggregating dataframe values and conducting sophisticated data analyses.

Code: [github.com/JunyiYe/dataframe-qa](https://github.com/JunyiYe/dataframe-qa)
