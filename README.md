# Step by step K-Means with Iris

This project provides a detailed step-by-step guide for applying K-Means clustering on the famous Iris dataset. The Iris dataset contains features of flowers from three different species, and K-Means is used to group them into clusters based on these features.

## Dataset

The Iris dataset consists of 150 samples, each with 4 features:
- Sepal length (cm)
- Sepal width (cm)
- Petal length (cm)
- Petal width (cm)

Target: 
- Setosa
- Versicolor
- Virginica

## Steps:

1. **Load Dataset:** Import the Iris dataset from `sklearn.datasets` and convert it into a Pandas DataFrame.
2. **Determine K Value:** Use the Elbow Method to determine the optimal number of clusters.
3. **Apply K-Means Algorithm:** Perform K-Means clustering with the optimal number of clusters.
4. **Visualize Results:** Use Matplotlib and Seaborn to visualize the clusters and centroid positions.

## Visualizations:

- Scatter plots showing the relationships between features (sepal and petal dimensions).
- Elbow method plot to determine the best number of clusters.
- Clustered data points with centroid positions.

## How to Use:

Clone this repository and run the `K-Means.ipynb` notebook step by step to see how K-Means clustering is applied on the Iris dataset.

### Dependencies:

- Python 3.x
- Pandas
- Matplotlib
- Seaborn
- scikit-learn

### Installation:

```bash
pip install -r requirements.txt
