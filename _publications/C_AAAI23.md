---
title: "Learning to Break Symmetries for Efficient Optimization in Answer Set Programming"
collection: publications
category: conferences
permalink: /publication/C_AAAI23
excerpt: ''
date: August 2023
venue: 'Proceedings of the AAAI Conference on Artificial Intelligence, (AAAI 2023)'
link: 'https://doi.org/10.1609/aaai.v37i5.25804'
#paperurl: 'https://academicpages.github.io/files/paper3.pdf'
citation: 'Tarzariol, A.; Gebser, M.;  Schekotihin, K.; and Law, M. (2023). &quot;Learning to Break Symmetries for Efficient Optimization in Answer Set Programming&quot;. <i>In Proceedings of the AAAI Conference on Artificial Intelligence, (AAAI 2023), </i> 37(5), (pp. 6541–6549).'
---
The ability to efficiently solve hard combinatorial optimization problems is a key prerequisite to various applications of declarative programming paradigms. Symmetries in solution candidates pose a significant challenge to modern optimization algorithms since the enumeration of such candidates might substantially reduce their performance. This paper proposes a novel approach using Inductive Logic Programming (ILP) to lift symmetry-breaking constraints for optimization problems modeled in Answer Set Programming (ASP). Given an ASP encoding with optimization statements and a set of small representative instances, our method augments ground ASP programs with auxiliary normal rules enabling the identification of symmetries using existing tools, like SBASS. Then, the obtained symmetries are lifted to first-order constraints with ILP. We prove the correctness of our method and evaluate it on real-world optimization problems from the domain of automated configuration. Our experiments show significant improvements of optimization performance due to the learned first-order constraints.