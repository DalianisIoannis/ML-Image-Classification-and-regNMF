Final Project for the Course Machine Learning - Pattern Recognition.

## Part 1: Data preprocessing, dimension reduction, image classification and visualization
Dataset of 30 colored images with landscapes in spring, fall and winter, 10 images for each season. Classify the images in a 2-dimensional plot using Principal Component Analysis.

Compare 1-NN and linear SVM classification accuracies on the dataset firstly using initial full-scale images and secondly using PCA-derived low-dimensional features.
Use 5-fold cross validation to report mean accuracy

## Part 2: regularized non-negative matrix factorization -regNMF

Implementation of an iterative algorithm to approach the optimal solution for the problem: 
$$\min_{W, C}∥X − WC∥^2_F + λ∥W∥^2_F + λ∥C∥^2_F s.t.W ≥ 0, C ≥ 0$$