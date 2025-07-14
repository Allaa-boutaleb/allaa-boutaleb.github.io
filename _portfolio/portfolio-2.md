---
title: "AI Engineer @ Sujet AI | 11/23 - Present | Paris, FR"
excerpt: "Co-founded Sujet AI, a startup democratizing financial analysis. Led the development and open-sourcing of foundational models (LLMs, VLMs, Embeddings) and large-scale datasets. Engineered a multi-agent system for advanced document analysis.<br/><img src='/images/sujet-ai.svg' width='300'>"
collection: portfolio
---

As a co-founder and AI Engineer at Sujet AI, I played a pivotal role in establishing the company's technical vision and leading the development of its core open-source contributions. Sujet AI is a Paris-based startup dedicated to democratizing investment opportunities by creating powerful, transparent, and accessible AI tools for financial analysis.

### Mission and My Role

The mission was to break down the barriers in financial analysis by providing open-source foundational models and high-quality datasets, enabling anyone from individual investors to large firms to leverage state-of-the-art AI. My work focused on two primary pillars: building the foundational technology and designing its practical application.

### Foundational Model and Dataset Development

A significant part of my role involved overseeing the entire lifecycle of our open-source models. This began with data curation and creation, where I led the effort to build several large-scale, specialized datasets for the financial domain, including:

* **Sujet-Financial-RAG-EN/FR**: Over 130,000 question-context pairs in English and French for training retrieval-augmented generation systems.
* **Sujet-Finance-QA-Vision-100k**: Nearly 10,000 image-based question-answer pairs from financial documents to train Vision-Language Models (VLMs).
* **Sujet-Finance-Instruct-177k**: A massive dataset of 178,000 instruction-following examples for fine-tuning LLMs on various financial tasks.

Using these datasets, I trained, fine-tuned, and released a suite of models on Hugging Face, including:

* **Marsilia Embeddings**: High-performance sentence-embedding models for finance in both English and French.
* **Lutece-Vision**: A VLM fine-tuned on financial documents for tasks like chart analysis and visual question answering.
* **Sujet-Finance-8B**: A fine-tuned Llama 3 model tailored for financial text generation, classification, and analysis.

### Multi-Agent Financial Analysis System

Beyond foundational models, I designed and engineered a multi-agent interface to serve as an "AI Copilot" for investment analysts. This system leverages our in-house models to perform complex tasks, such as conducting due diligence, gathering insights from dense financial reports (e.g., 10-Ks), and generating custom summaries. The multi-agent architecture allows for a sophisticated division of labor, where different AI agents can collaborate to analyze information, cross-reference data points, and synthesize findings into a coherent report.

### Current Status

As of today, my day-to-day involvement in Sujet AI has been reduced as I now focus on my PhD research obligations at Sorbonne University.

### Links

* **Website**: [sujet.ai](https://sujet.ai/)
* **Hugging Face**: [huggingface.co/sujet-ai](https://huggingface.co/sujet-ai)
* **LinkedIn**: [linkedin.com/company/sujet-ai](https://www.linkedin.com/company/sujet-ai/)


### Tools and Technologies

* **Programming Language**: Python
* **Core Libraries**: PyTorch, Hugging Face (Transformers, Datasets, Accelerate), LangChain, LlamaIndex
* **Models**: LLMs (Llama 3), VLMs (Florence-2), Sentence Transformers (SBERT)
* **Infrastructure**: Hugging Face Hub (for model and dataset hosting)