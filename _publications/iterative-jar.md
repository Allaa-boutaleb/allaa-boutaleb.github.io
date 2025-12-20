---
title: "Exploring Multi-Table Retrieval Through Iterative Search"
collection: publications
category: conferences
# permalink: /publication/2025-12-06-exploring-multi-table-retrieval
excerpt: 'Open-domain question answering over datalakes requires retrieving and composing information from multiple tables, a challenging subtask that demands semantic relevance and structural coherence (e.g., joinability). While exact optimization methods like Mixed-Integer Programming (MIP) can ensure coherence, their computational complexity is often prohibitive. This paper frames multi-table retrieval as an iterative search process, arguing this approach offers advantages in scalability, interpretability, and flexibility. We propose a general framework and a concrete instantiation: a fast, effective Greedy Join-Aware Retrieval algorithm that holistically balances relevance, coverage, and joinability. Experiments across 5 NL2SQL benchmarks demonstrate that our iterative method achieves competitive retrieval performance compared to the MIP-based approach while being 4-400x faster.'
date: 2025-12-06
venue: 'AI for Tabular Data Workshop @ EurIPS'
paperurl: 'https://openreview.net/forum?id=d64whXpOgf'
# codeurl: 'https://github.com/Allaa-boutaleb/iterative-jar'
citation: "Boutaleb, A., Amann, B., Angarita, R., & Naacke, H. (2025). Exploring Multi-Table Retrieval Through Iterative Search. Proceedings of AI for Tabular Data Workshop @ EurIPS 2025."
---

# Abstract
Open-domain question answering over datalakes requires retrieving and composing information from multiple tables, a challenging subtask that demands semantic relevance and structural coherence (e.g., joinability). While exact optimization methods like Mixed-Integer Programming (MIP) can ensure coherence, their computational complexity is often prohibitive. Conversely, simpler greedy heuristics that optimize for query coverage alone often fail to find these coherent, joinable sets. This paper frames multi-table retrieval as an iterative search process, arguing this approach offers advantages in scalability, interpretability, and flexibility. We propose a general framework and a concrete instantiation: a fast, effective Greedy Join-Aware Retrieval algorithm that holistically balances relevance, coverage, and joinability. Experiments across 5 NL2SQL benchmarks demonstrate that our iterative method achieves competitive retrieval performance compared to the MIP-based approach while being 4-400x faster depending on the benchmark and search space settings. This work highlights the potential of iterative heuristics for practical, scalable, and composition-aware retrieval.

# Links
* Paper: [openreview.net/forum?id=d64whXpOgf](https://openreview.net/forum?id=d64whXpOgf)
* Code & Data: [github.com/Allaa-boutaleb/iterative-jar](https://github.com/Allaa-boutaleb/iterative-jar)

```bibtex
@inproceedings{boutaleb2025exploring,
    title={Exploring Multi-Table Retrieval Through Iterative Search},
    author={Allaa Boutaleb and Bernd Amann and Rafael Angarita and Hubert Naacke},
    booktitle={EurIPS 2025 Workshop: AI for Tabular Data},
    year={2025},
    url={[https://openreview.net/forum?id=d64whXpOgf](https://openreview.net/forum?id=d64whXpOgf)}
}