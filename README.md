# FLDA
Implementing FLDA for the classification problems and reporting the metrics (Confusion Matrix, F1 Score, Accuracy, RoC, Likelihood Curve)

In linear discriminant analysis (LDA), the within-class scatter matrix (S_w) and the between-class scatter matrix (S_b) are used to project the data onto a lower-dimensional space while maximizing the class separability.

The within-class scatter matrix S_w measures the within-class variance of the data, i.e., the variance of the data points within each class. It is defined as the sum of the covariance matrices of each class.

The between-class scatter matrix S_b measures the between-class variance of the data, i.e., the variance between different classes. It is defined as the sum of the covariance matrices of the differences between the class means and the overall mean.

The FLDA algorithm maximizes the ratio of the determinant of S_b and S_w, so that the projected data has a larger between-class variance and a smaller within-class variance.
---------------------------------------------------
FLDA Log Likelihood Curve
-----------------
![FLDA Log Likelihood Curve](https://user-images.githubusercontent.com/101024664/230213017-3a63e60d-1fc0-420e-b630-1c6f646ad97e.png)
