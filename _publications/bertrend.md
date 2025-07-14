---
title: "BERTrend: Neural Topic Modeling for Emerging Trends Detection"
collection: publications
category: conferences
excerpt: "Detecting and tracking emerging trends and weak signals in large, evolving text corpora is vital for applications such as monitoring scientific literature, managing brand reputation, surveilling critical infrastructure and more generally to any kind of text-based event detection. Existing solutions often fail to capture the nuanced context or dynamically track evolving patterns over time. BERTrend, a novel method, addresses these limitations using neural topic modeling in an online setting. It introduces a new metric to quantify topic popularity over time by considering both the number of documents and update frequency. This metric classifies topics as noise, weak, or strong signals, flagging emerging, rapidly growing topics for further investigation. Experimentation on two large real-world datasets demonstrates BERTrend's ability to accurately detect and track meaningful weak signals while filtering out noise, offering a comprehensive solution for monitoring emerging trends in large-scale, evolving text corpora. The method can also be used for retrospective analysis of past events. In addition, the use of Large Language Models together with BERTrend offers efficient means for the interpretability of trends of events."
date: 2024-10-01
venue: 'FuturED @ EMNLP - Workshop on the Future of Event Detection'
paperurl: 'https://aclanthology.org/2024.futured-1.1.pdf'
citation: "Boutaleb, A., Picault, J., & Grosjean, G. (2024). BERTrend: Neural Topic Modeling for Emerging Trends Detection. EMNLP 2024 - Proceedings of the Workshop on the Future of Event Detection (FuturED), 1–17. Association for Computational Linguistics."

---

# Abstract
Detecting and tracking emerging trends and weak signals in large, evolving text corpora is vital for applications such as monitoring scientific literature, managing brand reputation, surveilling critical infrastructure and more generally to any kind of text-based event detection. Existing solutions often fail to capture the nuanced context or dynamically track evolving patterns over time. BERTrend, a novel method, addresses these limitations using neural topic modeling in an online setting. It introduces a new metric to quantify topic popularity over time by considering both the number of documents and update frequency. This metric classifies topics as noise, weak, or strong signals, flagging emerging, rapidly growing topics for further investigation. Experimentation on two large real-world datasets demonstrates BERTrend's ability to accurately detect and track meaningful weak signals while filtering out noise, offering a comprehensive solution for monitoring emerging trends in large-scale, evolving text corpora. The method can also be used for retrospective analysis of past events. In addition, the use of Large Language Models together with BERTrend offers efficient means for the interpretability of trends of events.

# Links
* Paper: [aclanthology.org/2024.futured-1.1.pdf](https://aclanthology.org/2024.futured-1.1.pdf)
* Code: [github.com/rte-france/BERTrend](https://github.com/rte-france/BERTrend)

# Citation

```bibtex
@inproceedings{boutaleb-etal-2024-bertrend,
    title = "{BERT}rend: Neural Topic Modeling for Emerging Trends Detection",
    author = "Boutaleb, Allaa  and
      Picault, Jerome  and
      Grosjean, Guillaume",
    editor = "Tetreault, Joel  and
      Nguyen, Thien Huu  and
      Lamba, Hemank  and
      Hughes, Amanda",
    booktitle = "Proceedings of the Workshop on the Future of Event Detection (FuturED)",
    month = nov,
    year = "2024",
    address = "Miami, Florida, USA",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2024.futured-1.1",
    pages = "1--17",
}
```
