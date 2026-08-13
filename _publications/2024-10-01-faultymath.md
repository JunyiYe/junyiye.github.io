---
title: "From Blind Solvers to Logical Thinkers: Benchmarking LLMs' Logical Integrity on Faulty Mathematical Problems"
collection: publications
category: preprints
permalink: /publication/2024-10-01-faultymath
excerpt: 'FaultyMath is a benchmark of logically flawed math problems used to test whether LLMs merely calculate or actually reason about problem validity.'
date: 2024-10-01
authors: "Muntasir Rahman*, Junyi Ye*, Wei Yao, Wenpeng Yin, Guiling Wang"
venue: 'arXiv preprint arXiv:2410.18921'
paperurl: 'https://arxiv.org/abs/2410.18921'
citation: 'Rahman*, M., Ye*, J., Yao, W., Yin, W., &amp; Wang, G. (2024). &quot;From Blind Solvers to Logical Thinkers: Benchmarking LLMs&#39; Logical Integrity on Faulty Mathematical Problems.&quot; <i>arXiv preprint arXiv:2410.18921</i>.'
---

Consider the math problem: "Lily received 3 cookies from her best friend yesterday and ate 5 for breakfast. Today, her friend gave her 3 more cookies. How many cookies does Lily have now?" Many LLMs solve this by calculating "1" using the equation "3 - 5 + 3." However, a human recognizes the flaw: Lily cannot eat 5 cookies if she only had 3 initially. This raises a critical question: are LLMs merely Blind Solvers that perform calculations without deeper reasoning, or can they act as Thinkers that identify logical inconsistencies? To investigate, we introduce **FaultyMath**, a benchmark of diverse faulty math problems spanning multiple categories (e.g., algebra, geometry), difficulty levels, and origins of faultiness (e.g., common sense violations, ambiguity, contradictions). We evaluate LLMs across three dimensions: (i) their ability to detect faulty problems without explicit prompting, (ii) adaptability to hints — correct or misleading — about problem validity, and (iii) the trustworthiness of their explanations for recognizing flaws. Our analysis shows that most LLMs operate as Blind Solvers, lacking the reasoning skills to function as Logical Thinkers.

Code: [github.com/JunyiYe/FaultyMathProblem](https://github.com/JunyiYe/FaultyMathProblem)
