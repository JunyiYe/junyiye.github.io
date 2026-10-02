---
title: "Can You Delete a Year of Market Data? Machine Unlearning Against Exact Retraining Oracles"
collection: publications
category: conferences
permalink: /publication/2026-09-13-market-data-unlearning
excerpt: 'A 3,200-model benchmark of temporal machine unlearning in financial forecasting against exact retraining oracles, showing when approximate deletion methods can close the reference-to-oracle gap.'
date: 2026-10-02
authors: "Junyi Ye"
venue: '7th ACM International Conference on AI in Finance (ICAIF 2026)'
paperurl: 'https://arxiv.org/abs/2609.26242'
citation: 'Ye, J. (2026). &quot;Can You Delete a Year of Market Data? Machine Unlearning Against Exact Retraining Oracles.&quot; <i>Proceedings of the 7th ACM International Conference on AI in Finance (ICAIF &#39;26)</i>.'
---

When a data license expires, deleting stored records does not remove influence encoded in a trained forecaster. Machine unlearning seeks to remove this influence without retraining. We benchmark temporal unlearning with 3,200 paired references trained on all data and oracles retrained without the requested period. The grid covers five architectures, four rolling folds, five deletable years, and three experimental deletion levels on an S&amp;P 500 volatility panel. The 2020 COVID crisis year produces the largest memorization gap for every architecture. Removing it improves all three deployable models in every fold, with the largest improvement in the 2022 bear market, while the two non-deployable models respond inconsistently. The target for approximate unlearning is the oracle, not low predictive accuracy on the deleted period. In one Transformer cell, an oracle that never trained on 2020 still predicts it at an information coefficient of 0.51, compared with 0.55 for the reference; pushing predictions toward noise reduces test skill. Across twelve deployable architecture-method pairs, only TSMixer with the hinge method remains near the oracle in every fold, closing 74-118% of the reference-to-oracle gap without a measurable loss of test skill. Method rankings vary across architectures and rolling windows. Audit separation rises with prior memorization but can remain small after exact deletion. The window-level loss comparison reaches at most 0.69, and treating stock-level windows as independent inflates the absolute t-statistic by a median factor of 1.9. These results call for an explicit deletion scope, oracle validation for the relevant architecture and window, and power-aware auditing.
