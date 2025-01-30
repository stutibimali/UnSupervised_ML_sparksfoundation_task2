# K-Means Clustering on Iris Dataset

This project demonstrates the application of K-Means clustering on the famous Iris dataset. It performs clustering, visualizes the clusters, and helps in identifying the optimal number of clusters using the Elbow Method.

## Requirements

Make sure to install the following Python libraries:
- `pandas`
- `numpy`
- `matplotlib`
- `scikit-learn`

You can install them using the following pip commands:
```bash
pip install pandas numpy matplotlib scikit-learn
```
Dataset
The dataset used is the Iris dataset, which contains the following features for each flower:

Sepal Length
Sepal Width
Petal Length
Petal Width
The dataset contains three different species of Iris flowers:

Iris-setosa
Iris-versicolour
Iris-virginica
Steps
1. Load the Dataset
The Iris dataset is loaded using pandas.read_csv from a CSV file located on your local machine.

2. Preprocess Data
The first column of the dataset (index) is removed, and only the relevant feature columns are retained.

3. Elbow Method
The Elbow Method is used to determine the optimal number of clusters by plotting the Within-Cluster Sum of Squares (WCSS) for different values of k (the number of clusters). The "elbow" point helps in selecting the best value for k.

4. Apply K-Means Clustering
The KMeans algorithm from scikit-learn is used to cluster the dataset into 3 clusters (based on the Elbow Method's recommendation). The clusters are then predicted for each data point.

5. Visualization
The results of clustering are visualized in the following ways:

Sepal Dimensions (Sepal Length vs Sepal Width)
Petal Dimensions (Petal Length vs Petal Width)
Each cluster is represented in different colors, and the centroids of the clusters are marked in yellow.

## How to Run
Download the Iris dataset (if you don't have it already) and place it in the correct path on your machine.
Run the Python script to see the clustering and visualizations.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

# sparksfoundation_task2 - Data classification Using Unsupervised Method (K- Means Clustering)
