---
title: "Research Assistant @ LIP6 | 06/23 - 09/23 | Paris, FR"
excerpt: "Conducted extensive investigations into the Aligned Neural Topic Model (ANTM), a novel dynamic topic modeling framework. Proposed and developed a methodology for detecting scientific paradigm shifts in large text archives using ANTM's topic evolution capabilities.<br/><img src='/images/lip6.png' height='300'>"
collection: portfolio
---

During my time as a Research Assistant at the LIP6 laboratory (Sorbonne University/CNRS), my work focused on the cutting edge of dynamic topic modeling. The central challenge was to move beyond static snapshots of topics and develop methods that could truly capture and interpret the evolution of concepts in large-scale text archives, such as scientific literature.

### Investigating the Aligned Neural Topic Model (ANTM)

My primary focus was conducting an in-depth investigation of the **Aligned Neural Topic Model (ANTM)**, a novel architecture designed to overcome the limitations of traditional dynamic topic models.

**The Problem:** Existing models often struggle to represent topic evolution accurately. They typically assume a fixed number of topics over time and use global clustering methods, which can obscure the emergence of new topics or the fading of old ones.

**The Solution (ANTM):** ANTM introduces a more flexible, algorithmic approach. Its core innovation is an **Aligned Clustering** process:
1.  **Time-Aware Embeddings:** It begins by using powerful language models to create contextual vector representations for all documents.
2.  **Sliding Window & Local Clustering:** The documents are segmented into overlapping time frames. Within each frame, ANTM performs local, density-based clustering (using UMAP and HDBSCAN) to identify topics relevant to that specific period. This allows the number of topics to naturally vary over time.
3.  **Alignment:** The model then intelligently aligns semantically similar topics across consecutive time frames, creating coherent "evolving topic" threads.

My work involved a deep dive into this framework, analyzing its components and contributing to the experiments that demonstrated its superior performance in generating more coherent and diverse topics compared to state-of-the-art baselines.

### Detecting Paradigm Shifts in Scientific Literature

Building on the capabilities of ANTM, I proposed and developed a methodology to use topic evolution as a means to detect major **paradigm shifts** in scientific fields. For example, how could we automatically identify the pivotal moment when "Transformers" began to supersede "RNNs" in NLP research?

My approach leverages the rich, temporal output of ANTM to identify signatures of such shifts within a large corpus like arXiv:
* **Topic Emergence & Growth:** A paradigm shift is often signaled by the rapid emergence of a new, highly coherent topic that quickly gains popularity (i.e., a high volume of associated papers).
* **Topic Decline:** Simultaneously, the previously dominant topic in that domain would show a marked decline in popularity.
* **Semantic Drift:** In some cases, a shift can be observed as a significant change in the core keywords of an existing topic, indicating that the field is redefining itself around new concepts.

This research explored how these quantitative signals, derived from ANTM's output, can serve as powerful, automated indicators of scientific revolution.

### Links

* **ANTM Paper (arXiv)**: [2302.01501](https://arxiv.org/abs/2302.01501)
* **GitHub Repository**: [ANTM-Investigations](https://github.com/Allaa-boutaleb/ANTM-Investigations)

### Tools and Technologies

* **Programming Language**: Python
* **Core Libraries**: PyTorch, Hugging Face (Transformers), Scikit-learn
* **Topic Modeling**: ANTM framework, BERTopic
* **Dimensionality Reduction & Clustering**: UMAP, HDBSCAN