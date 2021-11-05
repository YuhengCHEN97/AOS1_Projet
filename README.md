# AOS1_Projet

These are four projects carried out in the UTC machine learning course

## PCA - Regularization - Kernel Methods - Time Series

### PCA

Problem: band reduction in multispectral images**
A multispectral image is an image that has several components. For example, a color image
has 3 components: red, green and blue and each pixel can be viewed as a vector in R
3
. More
generally a multispectral image of size N × M with P spectral bands can be stored as a
N × M × P array. There are N × M pixels living in R
p
.
When the number of spectral bands P is too large, it is desirable to somehow reduce that
number ultimately to 3 for viewing purposes. This process is called band reduction.
Propose a method using the PCA performing a band reduction to 3 bands and use it on
the provided multispectral image.


### Regularization

Problem: make elastic net outshine the lasso

The elastic net regression was invented to compensate for the lack of robustness of the lasso regression. The elastic net especially outshines the lasso when some variables are highly correlated and on the same scale. You have been shown in the last course’s slides some intuitive arguments demonstrating why it should particularly be more robust in this case. But could you demonstrate this experimentally?

Design a regression dataset in which we want to select variables and where the elastic net gives better results in terms of stability of the set of selected variables.

### Kernel Methods
Problem:
The paper by Burges and Schölkopf [1] is investigating a method the improve the accuracy
and speed of SVM. First train a SVM with the same dataset (MNIST) with the kernel and
the hyperparameter C they are suggesting.
Describe the technique they are using to improve the accuracy and implement it to see if
it is working.

References

[1] [Chris J.C. Burges and Bernhard Schölkopf. “Improving the Accuracy and Speed of
Support Vector Machines”. In: Advances in Neural Information Processing Systems 9.
MIT Press, 1997, pp. 375–381.](https://proceedings.neurips.cc/paper/1996/file/b495ce63ede0f4efc9eec62cb947c162-Paper.pdf)

### Time Series
Problem:
The dataset in the ﬁle data/debitcards.csv stores the monthly retail debit card usage in Iceland (million ISK) from january 2000 to december 2012. Give an estimate of the cumulated debit card usage during the 4 ﬁrst months of 2013.

Particular care should be taken with the frequency of time series, its nature, the choice of the model and its validation.
