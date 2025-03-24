### Graph Centralities & Community Detection Analysis

This project focuses on the analysis of graph structures through **centrality measures**, **community detection**, and **node embeddings**. It combines visual and quantitative evaluations using multiple datasets and algorithms.

---

### Key Components

#### 1. **Graph Centrality Analysis**
- Evaluation of **degree**, **closeness**, **eigenvector**, and **PageRank** centralities.
- Distribution analysis and top-node identification.

#### 2. **Community Detection**
- Comparison of different algorithms:
  - **Louvain**
  - **Leiden**
  - **Girvan-Newman**
  - **Hierarchical Clustering**
- Metrics used: **Silhouette Score**, modularity, and visualizations.
- Applied to at least **two datasets** with detailed results.

#### 3. **Node Embedding & Clustering**
- Comparison between:
  - **Node2Vec**
  - **Spectral Embedding**
  - Optional: Pairwise encoder/decoder
- Visualization using **t-SNE + KMeans**
- Embedding quality evaluated by clustering structure and separation.

---

### Notebooks
- `DrugInteraction.ipynb`: Community and centrality analysis on biological interaction data.
- `github.ipynb`: Network representation and clustering based on GitHub project relations.

---

### Requirements
See `requirements.txt` for all package dependencies.

