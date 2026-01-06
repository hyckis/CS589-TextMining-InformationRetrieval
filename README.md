# CS589-TextMining-InformationRetrieval

This project implements and compares classical and neural retrieval models on the
StackOverflow dataset, building an end-to-end search and ranking pipeline.

### Methods
- Classical models: TF-IDF, BM25, Dirichlet Language Model
- Search backend: Elasticsearch
- Neural reranking: BERT-based ranker
- Optimization: Grid search & FLAML

### Evaluation
Models were compared using standard IR metrics (MAP, NDCG) to analyze the
performance gap between classical baselines and neural reranking approaches.


