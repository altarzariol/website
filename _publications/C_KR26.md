---
title: "ALM–ASP: A Functional Agentic Architecture for Answer Set Programming"
collection: publications
category: conferences
permalink: /publication/C_KR26
excerpt: ''
date: July 2026
venue: 'Proceedings of the 23rd International Conference on Principles of Knowledge Representation and Reasoning (KR 2026)'
link: 'https://doi.org/10.24963/kr.2026/103'
#paperurl: 'https://academicpages.github.io/files/paper3.pdf'
citation: 'Reiners, L. A. R.; Tarzariol, A.; Alviano, M.; Santana, M. B.; and Schekotihin, K. (2026). &quot;ALM–ASP: A Functional Agentic Architecture for Answer Set Programming&quot;. <i>In Proceedings of the 23rd International Conference on Principles of Knowledge Representation and Reasoning, (KR 2026), (pp. 1098-1108).</i>'
---

Answer Set Programming (ASP) is a declarative formalism widely used in knowledge representation and reasoning for modeling and solving combinatorial problems, yet current Large Language Models (LLMs) often struggle to generate correct programs from natural language specifications. This difficulty stems both from the limited presence of ASP in training corpora and from the strict syntactic and semantic constraints imposed by stable model semantics. We introduce ALM–ASP (Agentic Loop for Modeling in ASP), a multi-agent architecture for automatic ASP modeling grounded in a functional model of language agents equipped with tools and persistent state. ALM–ASP instantiates this model via two interacting agents: a Modeler, which incrementally constructs candidate ASP programs, and a Validator, which assesses their alignment with the original specification and provides feedback for refinement. The agents interact through a shared ASP execution environment backed by the CLINGO engine, yielding an iterative construct–validate loop. An empirical evaluation on a challenging subset of CP–Bench and on problems from recent LP/CP Programming Contests shows that ALM–ASP significantly improves both syntactic validity and end-to-end correctness over general-purpose LLM baselines, and also achieves improved instance coverage compared to the closest agentic alternative, CP–Agent.
