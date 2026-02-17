---
title: "Search-Embedding-lab"
collection: portfolio
share: false
excerpt: "Training Transformer Embeddings for Semantic Search."
github: "https://github.com/RishavAr/Search-Oriented-Transformer-Embeddings-for-Knowledge-Retrieval"

---

### 📦 Overview

 An end-to-end dense retrieval system for semantic search, focused on training embedding models from scratch, evaluating retrieval quality, and iterating on architecture design. The goal is to mirror how modern AI-native search systems are built: crawl → embed → index → retrieve → evaluate.

### 🧠 Approach

Query ──► Query Encoder ─┐
                         ├─► Similarity (dot / cosine) ─► Ranking
Docs  ──► Doc Encoder  ──┘

Training:
(Query, Positive Doc, Hard Negatives)
→ InfoNCE Contrastive Loss

Inference:
Query → FAISS ANN → Top-K Documents

### 📈 Findings
=== Retrieval metrics ===
K=  1  Recall@K=0.33   MRR=0.55   nDCG@K=0.66
K=  5  Recall@K=1.00   MRR=0.55   nDCG@K=0.66
K= 10  Recall@K=1.00   MRR=0.55   nDCG@K=0.66
K=100  Recall@K=1.00   MRR=0.55   nDCG@K=0.66
n_queries_eval: 6  

### 🔗 Links
- 💻 **Code:** [GitHub Repository](https://github.com/RishavAr/Search-Oriented-Transformer-Embeddings-for-Knowledge-Retrieval)
