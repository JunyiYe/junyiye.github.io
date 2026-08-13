---
title: "TextFlow"
excerpt: "Leveraging intermediate text representations for superior flowchart understanding<br/><img src='/images/textflow.svg'>"
collection: portfolio
---

Flowcharts are typically presented as images, driving the trend of using vision-language models (VLMs) for end-to-end flowchart understanding. However, two key challenges arise: (i) limited controllability, since users can only modify input images, and (ii) lack of explainability, since it is difficult to trace VLM errors to specific causes.

We propose **TextFlow** ([NAACL 2025](/publication/2025-01-22-textflow)), addressing these issues with two stages: a Vision Textualizer, which generates textual representations from flowchart images, and a Textual Reasoner, which performs question-answering based on those text representations. TextFlow offers three advantages: users can select the type of text representation (Graphviz, Mermaid, PlantUML), or convert it into an executable graph object; it improves explainability by attributing errors to visual or textual processing components; and it promotes modularization, allowing advanced LLMs to be used in the reasoner stage when VLMs underperform end-to-end. Experiments on the FlowVQA and FlowLearn benchmarks demonstrate TextFlow's state-of-the-art performance and robustness.

Code: [github.com/JunyiYe/TextFlow](https://github.com/JunyiYe/TextFlow)
