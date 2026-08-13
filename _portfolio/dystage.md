---
title: "DySTAGE"
excerpt: "Dynamic graph representation learning for asset pricing via spatio-temporal attention and graph encodings<br/><img src='/images/dystage.svg'>"
collection: portfolio
---

Current GNN-based asset price prediction models often focus on a fixed group of assets and their static relationships, overlooking the reality that asset pools and their interrelationships evolve over time.

We propose **DySTAGE** ([ICAIF 2024](/publication/2024-10-15-dystage)), a framework with a universal formulation that transforms asset pricing time series into dynamic graphs, accommodating asset addition, deletion, and changes in correlations. Assets at various historical time steps are structured as a sequence of dynamic graphs, where connections reflect long-term correlations. The Topological Module deploys Asset Influence Attention along with Asset-wise Importance Encoding, Pair-wise Spatial Encoding, and Edge-wise Correlation Encoding, while the Temporal Module captures node representations across time via attention. Experiments on three real-world stock pricing datasets show DySTAGE surpasses popular benchmarks in return prediction and offers profitable investment strategies.

Code: [github.com/JunyiYe/DySTAGE](https://github.com/JunyiYe/DySTAGE)
