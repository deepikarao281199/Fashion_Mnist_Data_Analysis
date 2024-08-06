# ANALYSIS OF FASHION-MNIST DATA

## INTRODUCTION

MNIST data is popular data set for image classification machine learning algorithms. Initially MNIST Data set is compromising of 10 class handwritten digits later it is modified into Fashion MNIST Data. Every fashion product on Za-lando has a set of pictures, demonstrating different aspects of the product.
They have used the front look thumbnail images of 70,000 unique products to build Fashion-MNIST dataset. Those products come from different gender groups: men, women, kids and neutral.


### ABSTRACT

Each image is 28 pixels in width and 28 pixels in height and a total of 784 pixels in total. Each pixel is associated with a single pixel-value, indicating the lightness or darkness of that pixel. This pixel-value is an integer between 0 and 255. The training and test data sets have 785 columns. ➢First column contains the class label (T shirt, Trouser..) ➢The Training data set has 60000 rows. The testing data set has 10000 rows. The data set is split into train data and test data in the ratio 0.85% and 0.15% respectively. From the graph it is evident that all labels are equally spread in the data set both test and train. Each Train and test sample is assigned to one of the following labels. 0 – T-shirt; 1 – Trouser etc., After proper preprocessing, the data is classified using the following models:

- Convolution Neural Network
- Logistic Regression
- Support Vector Classifier
- Naive Bayes
- Random Forest
- k-nearest neighbour
- Decision Tree 

The results of all the models are compared and viualization is done for all those.
