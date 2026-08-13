---
title: "Regime-Gated Residual Mixture-of-Experts for Cross-Sectional Volatility Forecasting"
collection: publications
category: preprints
permalink: /publication/2026-08-12-regime-gated-residual-moe
excerpt: 'RG-ResMoE routes regime information through expert gating rather than direct forecasting, improving cross-sectional volatility forecasting accuracy and training stability.'
date: 2026-08-12
venue: 'arXiv preprint arXiv:2608.12251'
paperurl: 'http://arxiv.org/abs/2608.12251'
citation: 'Ye, J., &amp; Borde, G. V. (2026). &quot;Regime-Gated Residual Mixture-of-Experts for Cross-Sectional Volatility Forecasting.&quot; <i>arXiv preprint arXiv:2608.12251</i>.'
---

Financial volatility is regime dependent, yet incorporating regime information into neural networks can also destabilize training. This paper asks where such information should enter a neural cross-sectional volatility forecasting model. We study five-day realized-volatility forecasts for 1,027 U.S. equities using a rolling walk-forward evaluation framework in which information, model capacity, hyperparameter tuning, and random seeds are matched across architectures. We propose **RG-ResMoE**, a regime-gated residual mixture-of-experts architecture in which regime information is used only for expert routing rather than for direct forecasting. The base predictor models volatility from stock features, while a gating network uses regime state variables to route residual corrections. RG-ResMoE consistently outperforms a capacity-matched MLP in both forecasting accuracy and training stability in the main U.S. study, with similar gains observed on an independent Japanese panel. The integration pathway is decisive: appending the same regime variables directly to the forecasting input degrades both predictive performance and training stability, whereas restricting them to the routing gate improves accuracy and Value-at-Risk calibration. Hard routing consistently underperforms soft routing. The results suggest that, in compact neural volatility forecasting models, the primary value of mixture-of-experts models lies less in increasing model capacity than in controlling how nonstationary regime information influences prediction.
