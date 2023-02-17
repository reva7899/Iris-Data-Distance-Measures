# Iris-Data-Distance-Measures
In this repository it shown how to for three different distance measures: Minkowski Distance, T-statistics Distance, and Mahalanobis Distance.

Minkowski Distance:
Minkowski distance is a generalization of other distance measures such as Euclidean distance and Manhattan distance. It is a distance measure that depends on an order parameter r. The Minkowski distance between two vectors A and B can be calculated using the following formula:
$D_{Minkowski}(A, B, r) = \left(\sum_{i=1}^n |a_i - b_i|^r \right)^{\frac{1}{r}}$

In this function, you will need to take three inputs: vector A, vector B, and order r. The function should return the Minkowski distance between the two input vectors.

T-Statistics Distance:
T-statistics distance is a statistical measure that is commonly used to compare two sets of data. It is calculated as the difference between the means of the two sets of data, divided by the standard deviation of the difference. The T-statistics distance between two vectors A and B can be calculated using the following formula:
$D_{T-statistics}(A, B) = \frac{\bar{A} - \bar{B}}{\sqrt{\frac{1}{n_A} + \frac{1}{n_B}}\times S}$

In this function, you will need to take two inputs: vector A and vector B. The function should return the T-statistics distance between the two input vectors.

Mahalanobis Distance:
Mahalanobis distance is a distance measure that takes into account the correlation between the different features in a dataset. It is commonly used in multivariate analysis to compare observations with each other. The Mahalanobis distance between two vectors A and B can be calculated using the following formula:
$D_{Mahalanobis}(A, B, M) = \sqrt{(A-B)M^{-1}(A-B)^T}$

In this function, you will need to take three inputs: vector A, vector B, and covariance matrix M. The function should return the Mahalanobis distance between the two input vectors.

Overall, these three distance measures are commonly used in data analysis and can help provide insight into the relationships between different data points. Writing functions to calculate these distances can be useful in a variety of data analysis tasks.
