# Iris-Dataset-Comparative-Analysis

This project compares the performance of various clustering algorithms using different preprocessing techniques on the Iris dataset.

## Algorithms Compared
- KMeans
- Agglomerative Clustering
- DBSCAN

## Preprocessing Techniques
- StandardScaler
- MinMaxScaler
- Normalizer

## Evaluation Metrics
- Silhouette Score
- Calinski-Harabasz Index
- Davies-Bouldin Score

## Dataset
Iris Dataset from UCI ML Repository

## Results

| Scaler        | Algorithm     | n_clusters | Silhouette Score | Calinski-Harabasz | Davies-Bouldin |
|---------------|---------------|------------|------------------|-------------------|----------------|
| StandardScaler | KMeans       | 3          | 0.553            | 561.627           | 0.661          |
| ...           | ...           | ...        | ...              | ...               | ...            |

## Conclusion
- StandardScaler with KMeans performed best with 3 clusters.
- DBSCAN showed fewer clusters, sensitive to scaling.
- Silhouette Score was highest for KMeans + StandardScaler combo.

## Files
- `Clustering_Analysis.ipynb`
- `clustering_comparison_results.csv`
