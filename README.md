# PCA-Based Dimensionality Reduction and Classification of MNIST Digits
# MNIST Handwritten Digit Classification using PCA

This project explores Principal Component Analysis (PCA) as a dimensionality-reduction technique for handwritten digit recognition using the MNIST dataset.

MNIST consists of grayscale images of handwritten digits from 0 to 9, where each image contains 28 × 28 pixels. Therefore, every image can initially be represented as a 784-dimensional feature vector.

The primary objective of this project is to investigate whether the dimensionality of the image data can be significantly reduced using PCA while preserving the information required for accurate digit classification.

# Objectives:
- Understand the application of PCA to high-dimensional image data.
- Analyze the variance captured by different principal components.
- Reduce the dimensionality of the MNIST feature space.
- Visualize the transformed data in lower dimensions.
- Train a classification model, KNeighborsClassifier using PCA-transformed features.
- Evaluate the effect of dimensionality reduction on prediction performance.

# Principal Component Analysis

- PCA is applied to identify directions of maximum variance in the data.
- The principal components provide a new coordinate system in which the original 784-dimensional data can be represented using substantially fewer dimensions.

# Explained Variance Analysis

- The variance explained by individual principal components and the cumulative explained variance are analyzed.
- This helps determine an appropriate number of components that can represent most of the information contained in the original dataset.

📊 Dataset

The MNIST (Modified National Institute of Standards and Technology) dataset contains grayscale images of handwritten digits ranging from 0 to 9.

Each image has:
- Image size: 28 × 28 pixels
- Original feature dimension: 784
- Classes: 10 (digits 0–9)

Before applying PCA, the image pixels are transformed into numerical feature vectors suitable for machine-learning algorithms.



🛠️ Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook

# 💡 Key Insights
- MNIST images have a high-dimensional representation of 784 pixel features.
- Many of these features contain redundant or less informative information.
- PCA provides a compact representation by projecting the data onto directions of maximum variance.
- Explained-variance analysis can be used to select an appropriate number of principal components.
- Dimensionality reduction can substantially decrease the feature space presented to the classifier while preserving important information.
- The project demonstrates the practical connection between linear algebra, statistics, dimensionality reduction, and machine learning.


