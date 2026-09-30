# Sushant Patil

Data Scientist, Mumbai

Applied ML · ML systems · RAG · experimentation

I work on systems that continue past model training, experimentation and evaluation, then serving and production behavior.

Professionally, that is forecasting, experimentation, and optimization on production ML systems.

## What I work on

- **Applied ML** : forecasting, optimization, experimentation, and model evaluation
- **ML systems** : inference, model lifecycle, APIs, monitoring, and production behavior
- **Retrieval and RAG** : retrieval strategies, reranking, and separate evaluation of retrieval and answers
- **ML foundations** : how algorithms optimize, regularize, and fail

## Selected projects

### [RAGBench](https://github.com/sush4nt/rag-bench)

Compares lexical, semantic, hybrid, and reranked retrieval on the same questions and the same documents.

NDCG, MRR, Recall, and latency are scored apart from answer faithfulness, so a better ranker does not hide a worse answer.

`BM25` `Dense retrieval` `Reranking` `RAGAS` `Qdrant`

### [MLServe](https://github.com/sush4nt/mlserve)

Trains, versions, and serves models, then measures how the serving runtime behaves.

The same XGBoost weights run through a Python runner and an ONNX runtime on a KServe V2 API. MLflow versions the models. Prometheus and Grafana record latency, throughput, and errors.

`FastAPI` `MLflow` `ONNX` `Prometheus` `Grafana`

### [ML Core](https://github.com/sush4nt/ml-core)

Classical algorithms implemented in NumPy — linear and logistic regression, trees, boosting, naive Bayes, and a linear SVM — behind one fit/predict interface.

Built to study optimization, regularization, split criteria, and convergence, and to compare that behavior with library implementations.

`NumPy` `Optimization` `Model behavior`

## Stack

**ML** : Python · NumPy · scikit-learn · XGBoost

**Systems** : FastAPI · MLflow · Docker · Kubernetes

**Observability** : Prometheus · Grafana

**Data** : SQL · PySpark

**AI** : RAG · retrieval evaluation

## Currently exploring

RAG evaluation · retrieval systems · inference performance · production ML

[LinkedIn](https://www.linkedin.com/in/sush4nt/) · [Portfolio](https://sushantpatil.dev) · [Email](mailto:sushant.kb.patil@gmail.com)
