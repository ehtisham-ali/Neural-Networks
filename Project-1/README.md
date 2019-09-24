# Multiple Regression - Stochastic Gradient Descent

Problem-1
Features are our friends for prediction. For example, knowing the weight of a person is helpful for predicting his/her height. Knowing both the weight and age may improve the accuracy of our prediction. However, too many features could harm: each feature can be thought of as a dimension,  𝑛  features correspond to a  𝑛  dimensional space. In a high dimensional space ( 𝑛  is very large), our data will distribute sparsely: if you draw unit grids in the space, the most of them will contain no data, which obstructs the learning process. This is called the curse of dimensionality (for more detail about the curse of dimensionality, see here).

To overcome the curse of dimensionality, we simply reduce the dimensionality (i.e. reduce the number of features). We can either select a subset of all features, or we can apply PCA on our dataset. By specifying a  𝑑  ( 𝑑 < 𝑛 ), PCA will project our  𝑛  dimensional data onto a  𝑑  dimensional (affine) space. The assumption is that classification/regression should be easier in this  𝑑  dimensional space.

Dimensioanlity reduction via PCA is implemented in this exercise.



Problem-2
In this exercise I dealed with multiple linear regression. Performing regression on one independent (or explanatory) variable and a scalar dependent variable is called simple linear regression. But, when there are more than one explanatory variable (i.e.  𝑥(1),𝑥(2),...,𝑥(𝑘) ), and a single scalar dependent variable (y), then it's called multiple linear regression. (Please don't confuse this with multivariate linear regression where we predict more than one (correlated) dependent variable.)

Here, I implemented a multiple linear regression model in Python/NumPy using the Gradient Descent algorithm. Particularly, I used stochastic gradient descent (SGD) where one performs the update step using a small set of training samples of size batch_size which is set to 64.
 

## File Description

The project contains the following files:

  - `SGD_MultiRegression.py`: 




