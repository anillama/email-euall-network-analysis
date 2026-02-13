# Email Network Analysis – SNAP email-EuAll Dataset

## Project Overview

This project analyzes a large-scale directed email communication network from the Stanford SNAP dataset email-EuAll.

The objective is to explore structural properties of real-world communication networks using graph mining techniques and to extend the analysis with advanced network modeling approaches.

This project is part of a Data Mining / Network Analysis course and is being developed as a professional portfolio project.

## Dataset Information

- **Dataset Name:** email-EuAll  
- **Source:** Stanford SNAP (Stanford Network Analysis Project)  
- **Type:** Directed graph  
- **Nodes:** 265,214  
- **Edges:** 420,045  
- **Description:** Email communication network from a large European research institution (anonymized)  

The dataset is automatically downloaded from SNAP within the notebook to keep the repository lightweight.

## Project Goals
### Core Graph Mining Tasks
- Directed graph construction
- In-degree and out-degree distribution analysis
- Network density and sparsity analysis
- Weakly connected component analysis
- Centrality measures
- PageRank

### Planned Advanced Extensions
- Node embeddings (e.g., Node2Vec)
- Link prediction
- Community detection
- Anomaly detection
- Graph Neural Networks (GNNs)

## Exploratory Data Analysis (EDA) – Key Insights
- The network is extremely sparse.
- Degree distributions are highly skewed (power-law-like behavior).
- A small number of nodes act as communication hubs.
- Many small disconnected components exist outside the largest weakly connected component.
- Communication activity is highly heterogeneous across users.

These findings motivate embedding-based and community-aware modeling techniques.

## Research Questions
- How does node centrality relate to communication behavior?
- Can structural embeddings identify similar users?
- Can we predict potential future communication links?
- Do detected communities reflect organizational structure?

## Technologies Used
- Python
- NetworkX
- Pandas
- Matplotlib
- Jupyter Notebook
