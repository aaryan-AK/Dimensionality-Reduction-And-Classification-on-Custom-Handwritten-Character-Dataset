# Dimensionality-Reduction-And-Classification-on-Custom-Handwritten-Character-Dataset
## Done During Sep 2022 - Oct 2022

---

In this project, I worked with a custom handwritten character dataset and implemented dimensionality reduction and manifold learning techniques for visualization and subsequent classification tasks to report on a set of questions.

The goal of this assignment include:

1.  Dataset visualization and interpretability via dimensionality reduction
2. Implement dimensionality reduction techniques with scikit-learn
3. Carry out experiments to select best subspace projections
4.  Design pipelines for hyperparameter tuning and model selection
5.  Implement performance evaluation metrics and evaluate results

---
### Assignment

1. Implement Recursive Feature Elimination (RFE) to select the subset of features. Experiment with at least 2 different estimators.

  * Identify which pixels are selected and display mask examples from the training dataset.
2. Implement Principal Component Analysis (PCA) to select the number of components that explain at least 90% of the explained variance. Train a classifier on the original dataset and the reduced dataset.
  * Was training faster using the reduced dataset?
  * Compare performances.
  * Visualize the top 10 eigenvectors. Discuss what they represent.
  * Visualize examples of image reconstruction from PCA projections.
3. Use Fisher's Linear Discriminant Analysis (LDA) and t-SNE to reduce the dataset to 2 dimensions and visualize it.
  * Visualize the dataset, be sure to color-code each point to its corresponding target label.
  * How many features would you select? Why?
  * Visualize and compare the 2-dimensional projections with PCA. Discuss your observations.
4. Implement at least 3 manifold learning algorithms for reducing the dimensionality of the feature space. Utilize the new lower-dimensional feature space to build a classifier.
  * Visualize and interpret the first 2 dimensions in the manifold learning algorithm trained.

---

### Custom Handwritten Characters Dataset

The dataset you will be working with is available for download here:

* ["data_train.npy"](https://ufl.instructure.com/files/72621855/download?download_frd=1)
* ["labels_train.npy"](https://ufl.instructure.com/files/72621858/download?download_frd=1)
* ["data_test.npy"](https://ufl.instructure.com/files/72621555/download?download_frd=1)
* ["labels_test.npy"](https://ufl.instructure.com/files/72621857/download?download_frd=1)

  ---
  
