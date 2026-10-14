GiftLane Recommendation Engine

A collaborative filtering recommendation engine built for GiftLane utilizing low-rank matrix factorization (Truncated SVD vs. PCA) and K-Means customer segmentation.

Features

Factorizes sparse user-item purchase matrices into latent embeddings for recommendations.
Benchmarks Truncated SVD against PCA on explained variance, training time, and memory footprint.
Clusters customers using K-Means and profiles each segment by top purchased products and countries.
Evaluates recommendation performance using Hit Rate @ 10 against a traditional best-seller baseline.

Required Libraries
pip install numpy pandas scikit-learn scipy pickle
