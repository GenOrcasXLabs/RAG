# Retrieval-Augmented Generation (RAG)

A practical learning repository covering Retrieval-Augmented Generation (RAG) from basic retrieval techniques to advanced and agentic architectures.

## What is RAG?

Retrieval-Augmented Generation (RAG) is an approach that retrieves relevant information from an external knowledge source and provides it to a Large Language Model (LLM) to generate accurate and context-aware responses.

## RAG Roadmap

### 01. Basic RAG

Fundamental RAG concepts and workflows.

* Naive RAG
* Document Loading
* Chunking
* Embeddings
* Vector Stores
* Retrieval
* Context Generation
* LLM Response Generation

### 02. Advanced RAG

Techniques designed to improve retrieval quality, relevance, and answer accuracy.

* Hybrid RAG
* Fusion RAG
* Corrective RAG
* Query Expansion
* Reranking

### 03. Agentic RAG

RAG systems that use agents to dynamically plan, retrieve, evaluate, and decide how to answer a query.

* Agentic RAG
* Adaptive RAG
* Query Planning
* Iterative Retrieval
* Retrieval Evaluation

## Repository Structure

```text
RAG/
│
├── README.md
│
├── 01_Basic_RAG/
│   └── Naive_RAG_with_Langchain.ipynb
│
├── 02_Advanced_RAG/
│   ├── Hybrid_RAG.ipynb
│   ├── Fusion_RAG.ipynb
│   └── Corrective_RAG.ipynb
│
└── 03_Agentic_RAG/
    ├── Agentic_RAG.ipynb
    └── Adaptive_RAG.ipynb
```

## Technologies

* Python
* LangChain
* Hugging Face
* ChromaDB
* Groq
* Jupyter / Google Colab

## Learning Approach

Each implementation focuses on understanding the underlying RAG workflow through hands-on, step-by-step notebooks rather than relying only on high-level abstractions.

## Goal

Build a strong understanding of how RAG systems evolve from simple retrieval pipelines into advanced and agentic AI systems.
