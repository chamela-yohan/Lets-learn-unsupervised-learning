Unsupervised Learning from Scratch – K-Means Clustering
📌 Project Overview

This project demonstrates unsupervised learning by implementing the K-Means clustering algorithm from scratch using only basic Python libraries.
The goal is to understand how clustering works internally without relying on high-level machine learning frameworks.

Synthetic data is used so that every step of the algorithm is fully transparent and easy to reason about.

🎯 Learning Objectives

By completing this project, you will understand:

What unsupervised learning is and how it differs from supervised learning

The core idea of clustering

How the K-Means algorithm works step by step

Euclidean distance and centroid updates

Why K-Means converges

Common limitations of K-Means (important for interviews)

🧠 Key Concepts Covered

Unsupervised Learning

Clustering

Euclidean Distance

Centroids

Iterative Optimization

Convergence Criteria

🧪 Dataset

Type: Synthetic (generated using NumPy)

Features: 2D points

Clusters: 3 natural groups

Why synthetic?

No hidden preprocessing

Easy to visualize

Full control over data distribution

🛠️ Technologies Used

Python

NumPy – numerical computations

Matplotlib – data visualization

❌ No machine learning libraries (e.g., scikit-learn) were used.

⚙️ How the Algorithm Works

Randomly initialize K centroids

Assign each data point to the nearest centroid (Euclidean distance)

Recalculate centroids as the mean of assigned points

Repeat until centroids stop changing or maximum iterations are reached

📊 Output

Visual plot showing clustered data points

Final centroid positions highlighted

Color-coded clusters

🚧 Limitations of K-Means

Requires choosing K in advance

Sensitive to centroid initialization

Assumes spherical and equally sized clusters

Sensitive to outliers

📁 Project Structure
.
├── kmeans_from_scratch.py
├── README.md

🚀 Next Steps

Planned extensions for this project:

Elbow Method for choosing optimal K

Improved centroid initialization (K-Means++)

Comparison with other clustering techniques

Applying clustering to real-world datasets

Transitioning to interview-ready, industry-level implementations

✍️ Author

Chamela Yohan
Aspiring Machine Learning Engineer
Focused on understanding ML fundamentals from first principles