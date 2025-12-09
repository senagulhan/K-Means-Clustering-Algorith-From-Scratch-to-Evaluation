# K-Means Clustering: From Scratch to Evaluation

In this project, I implemented the K-Means clustering algorithm from scratch using basic Python libraries. The purpose was to better understand how the algorithm actually works, rather than using a built-in function from a machine learning library.

## 🛠️ Tools Used

- Python (NumPy, Matplotlib, Seaborn)
- Google Colab
- Dataset generated using `make_blobs` from scikit-learn

## 📌 What I Did

- Created a 2D dataset with 4 cluster centers
- Standardized the data using `StandardScaler`
- Implemented the full K-Means algorithm manually:
  - Initialized random centroids
  - Assigned points to the nearest centroid
  - Recalculated centroids as the mean of assigned points
  - Repeated the process until convergence or max iteration
- Tracked centroid positions at each step
- Visualized the clustering results

## 📊 Visualization

- Scatter plots show the original data and clustering results
- Centroid positions are marked with red `+` signs
- Also visualized centroid movements at a selected iteration

## 💡 Notes

- No machine learning libraries were used for the clustering logic
- The `evaluate()` method returns both cluster labels and matched centroids
- Useful for learning how unsupervised algorithms like K-Means work under the hood

---

This project was a learning exercise, and I’m planning to try this on real-world data or add evaluation metrics like silhouette score in the future.
