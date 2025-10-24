# 🔎 Information Retrieval

> From keyword search to semantic retrieval — connecting queries and documents through vector representations.

---

## 🧩 Concepts
Information Retrieval (IR) focuses on finding relevant documents given a query.

Covered topics:
- Vector Space Model (TF-IDF)
- Probabilistic ranking (BM25)
- Query expansion
- Semantic search with embeddings (e.g. BERT)
- Evaluation of ranking systems

---

## ⚙️ Implementation Plan

- [ ] Implement TF-IDF retrieval using scikit-learn  
- [ ] Build BM25 ranker (via rank-bm25 or manual implementation)  
- [ ] Add query preprocessing (tokenization, lemmatization)  
- [ ] Integrate semantic embeddings (Sentence Transformers)  
- [ ] Build simple search interface  
- [ ] Evaluate ranking performance  

---

## 📊 Evaluation Metrics

- Precision@K  
- Recall@K  
- Mean Average Precision (MAP)  
- Normalized Discounted Cumulative Gain (nDCG)  
- MRR (Mean Reciprocal Rank)

---

## 🧪 Experiments & Insights

- Compare keyword-based vs semantic retrieval  
- Test influence of preprocessing on ranking  
- Visualize document embeddings in 2D space  
- Measure trade-offs between recall and precision  
- Observe query drift with expansion terms  

---

## 📚 Resources

- *Introduction to Information Retrieval* — Manning, Raghavan, Schütze  
- *Search Engines: Information Retrieval in Practice* — Croft et al.  
- ElasticSearch / Whoosh / rank-bm25  
- Hugging Face Sentence Transformers  

---

## ✅ Progress

- [ ] TF-IDF implemented  
- [ ] BM25 benchmarked  
- [ ] Semantic search tested  
- [ ] Metrics evaluated  
- [ ] Insights documented  
