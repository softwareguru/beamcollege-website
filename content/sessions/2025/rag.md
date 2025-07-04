---
title: 'Building Scalable Semantic Search and RAG Pipelines'
date: 2025-04-01T12:09:13-05:00
instructors:
 - Claude van der Merwe
time_start: 2025-05-16T15:00:00.000Z
time_end:   2025-05-16T15:30:00.000Z
track: New features
summary: "This presentation introduces vector-based semantic search and Retrieval Augmented Generation (RAG), demonstrating how to build scalable pipelines for using Apache Beam. We'll start by explaining fundamental concepts like chunking, embeddings and vector similarity. Then we'll explore semantic search applications before extending to full RAG systems."
slides: 2025/BuildingScalableSemanticSearchAndRAGPipelines.pdf
video: https://youtu.be/y4vdVoX9K5g
---

This presentation introduces vector-based semantic search and Retrieval Augmented Generation (RAG), demonstrating how to build scalable pipelines for using Apache Beam. We'll start by explaining fundamental concepts like chunking, embeddings and vector similarity. Then we'll explore semantic search applications before extending to full RAG systems. 

The presentation walks through implementing both semantic search and RAG pipelines using Apache Beam's ML components, covering data ingestion, chunking, embedding generation, vector database integration, and similarity search. By the end, students will understand the theoretical foundations of both systems and have practical knowledge of how to implement them at scale using Apache Beam's distributed processing capabilities.

#### Resources: 

* [Beam RAG documentation](https://beam.apache.org/releases/pydoc/current/apache_beam.ml.rag.html) 
* [Beam RAG code repository](https://github.com/apache/beam/tree/master/sdks/python/apache_beam/ml/rag)
* [Notebook: Embedding Ingestion and Vector Search with Apache Beam and BigQuery](https://github.com/apache/beam/blob/master/examples/notebooks/beam-ml/bigquery_vector_ingestion_and_search.ipynb)
* [Notebook: Vector Embedding Ingestion with Apache Beam and AlloyDB](https://github.com/apache/beam/blob/master/examples/notebooks/beam-ml/alloydb_product_catalog_embeddings.ipynb)
