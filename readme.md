# MachineLearning_EEG
Machine learning study course for EEG

## Study materials
-

## 1 Basics
- What is machine learning?
- Supervised and Unsupervised learning
- Dataset segmentation (Training, Validation and Test dataset)

## 2 Feature extraction
- Time-series ERP amplitude properties
  - Maximum value
  - Minimum value
  - Arithmetic mean value
  - Standard deviation
  - Medium
  - Variance
  - Skewness coefficient
  - Kurtosis coefficient
  - Number of zero crossing
  - Entropy
  - Mean energy value
- Spectral properties
  - Fourier Transform
  - Wavelet Transform
    - DWT
    - CWT
- Spatial properties
  - Frontal Alpha Assymetry

## 3 Feature selection
- Shrinking method
  - [LASSO: L1 norm](http://blueskyvision.tistory.com/193)
  - Ridge: L2 norm
- Dimension reduction
  - Principal Component Analysis (PCA)
  - Common Spatial Filter (CSP)
  - Partial Least Square (PLS)
  - Autoencoder (Non-linear)

## [4 Classifier](https://github.com/tyami/ml-eeg/blob/master/tyang_ml_classifier.pdf)
- Supervised learning
  - Linear Regression
  - Naive Bayes Classifier
  - Discriminant Analysis (DA)
  - Support Vector Machine (SVM)
  - Multi layer Perceptron (MLP)
  - Random Forest
- Unsupervised learning
  - K-Nearest Neighborhood (K-NN)
  - K-means clustering

## 5 Cross validation
 - What is cross validation?
   - Leave-one-out cross validation
   - K-fold cross validation
 - Subject-wise leave-one-out cross validation
 - Across-subject leave-one-subject-out cross validation

## [6 Optimizer](https://github.com/tyami/ml-eeg/blob/master/tyang_ml_optimizer.pdf)
 - Gradient descent
   - Full-batch
   - Stochastic
   - Mini-batch
 - Momentum
 - Regularization (Weight decay)
 
## Machine leaning terms
 - Variance-Bias Trade-off
