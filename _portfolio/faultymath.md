---
title: "FaultyMath"
excerpt: "Benchmarking LLMs' logical integrity on faulty mathematical problems<br/><img src='/images/faulty_math_problem.svg'>"
collection: portfolio
---

Consider the math problem: "Lily received 3 cookies from her best friend yesterday and ate 5 for breakfast. Today, her friend gave her 3 more cookies. How many cookies does Lily have now?" Many LLMs solve this by calculating "1" using the equation "3 - 5 + 3." A human recognizes the flaw: Lily cannot eat 5 cookies if she only had 3 initially. Are LLMs merely Blind Solvers, or can they act as Thinkers that identify logical inconsistencies?

We introduce **FaultyMath** ([preprint](/publication/2024-10-01-faultymath)), a benchmark of diverse faulty math problems spanning multiple categories, difficulty levels, and origins of faultiness (e.g., common sense violations, ambiguity, contradictions). We evaluate LLMs across three dimensions: their ability to detect faulty problems without explicit prompting, adaptability to hints about problem validity, and the trustworthiness of their explanations for recognizing flaws. Our analysis shows that most LLMs operate as Blind Solvers, lacking the reasoning skills to function as Logical Thinkers.

Code: [github.com/JunyiYe/FaultyMathProblem](https://github.com/JunyiYe/FaultyMathProblem)
