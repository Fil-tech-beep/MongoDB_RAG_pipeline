# MongoDB RAG Pipeline

A custom Retrieval-Augmented Generation (RAG) pipeline built from scratch to query Isaac Asimov's *Foundation* PDF using MongoDB Vector Search and Hugging Face LLMs.

* **Workflow:** Custom PDF chunking $\rightarrow$ `all-mpnet-base-v2` embeddings $\rightarrow$ MongoDB Vector Store $\rightarrow$ Cosine Similarity Search $\rightarrow$ Hugging Face LLM generation.
* **Tech Stack:** Python, PyMongo, Sentence-Transformers, Hugging Face API.
* **Disclaimer:** Unfiltered commentary and original profanity have been left intact for the full, authentic experience.
