# MNIST-digit-clustering

In this case study we will work on the **MNIST** dataset and will **cluster the images in six groups** using the **t-SNE** dimensionality reduction technique. We'll also identify and visualize the clusters using the **K-Mean** algorithm.

**Note:** We will use the datasets module of the sklearn library to load the data and will only consider 6 classes, i.e., **digits from 0 to 5**.

## **Context**

- **1083 different images** each one with **64 dimensions** were loaded from the MNIST dataset. Those images correspond to the digits from 0 to 5. The main idea is to reduce the number of dimensions of the images, from **64 to 2** using t-SNE in order to visualize the distribution of images in 2 dimensions. Then, apply the Kmean algorithm in order to cluster the data.

## **Results**

![image](https://github.com/danieljordan2/MNIST-digit-clustering/assets/86810694/9fcfa6ff-bd4a-4350-b6b7-162091798981)

The K-means clustering algorithm was able to identify the digit clusters in the data.

## **Conclusion**

- We have effectively reduced the dimensionality of the images, from 64 to 2, using t-SNE and plotted the 2D embeddings.
- K-mean algorithm is good for clustering well differenciated data with no outliers.
- It's very useful to combine a dimensionality reduction algorithm (like t-SNE) with K-mean in order to cluster and visualize complex data.
