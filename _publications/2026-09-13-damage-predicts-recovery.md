---
title: "Damage Predicts Recovery: When Calibration Data Matters in Compressing Financial LLMs"
collection: publications
category: conferences
permalink: /publication/2026-09-13-damage-predicts-recovery
excerpt: 'A study across two model families and ten financial tasks showing that calibration-corpus choice for compressing LLMs only matters when compression causes large task-specific damage.'
date: 2026-10-02
authors: "Junyi Ye, Mengjia Yu, Debapriya Hazra, Guiling Wang"
venue: 'ICAIF 2026'
paperurl: 'https://arxiv.org/abs/2609.26241'
citation: 'Ye, J., Yu, M., Hazra, D., &amp; Wang, G. (2026). &quot;Damage Predicts Recovery: When Calibration Data Matters in Compressing Financial LLMs.&quot; <i>Proceedings of the 7th ACM International Conference on AI in Finance (ICAIF &#39;26)</i>.'
---

Post-training quantization and pruning rely on a small calibration corpus. Whether specialized domains such as finance require domain-matched calibration data remains unsettled. We argue that the answer depends on the task-level damage caused by compression rather than on domain mismatch. If compression preserves the target capability, changing the calibration corpus has little effect. If compression causes large losses, task-formatted calibration can recover part of the loss. We test this hypothesis across two model families, six compression configurations, three token-matched calibration corpora, and ten financial classification and numerical question-answering tasks. The results support this hypothesis. Quantization largely preserves task performance, and calibration choice has little effect in this case. Pruning reduces numerical QA accuracy by over 40 points. In these damaged settings, another generic corpus does not help, while FinMix, a mixture of financial task examples, recovers a large part of the loss. The link between damage and recovery holds across model families and scales. These findings support a practical rule. Measure task-specific compression damage first, and construct specialized calibration data only when the damage is large.
