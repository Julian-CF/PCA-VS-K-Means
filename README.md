# PCA vs K-Means

This project computes the Principal Component Analysis and K-Means algorithms and use them on a dataset. The dataset is the set of images from MNIST database corresponding to the handwritten digit 7. Each image is 28 pixels times 28 pixels. The set is divided in a training set and a testing set of respective size 3133 and 3132.

### Comparison
After the implementation of both algorithm a comparison of the results from PCA to the results of K-means on the <b>test set</b> is given by plotting on the same graph the reconstruction error E(D) for D = 3,4,5,10,50,100 and the distortion cost (remark that the two measures are simply L_2 norms thus the comparison is valid). To be clear, the first one measure the error in the reconstructed image from the projection on the components of PCA, the second measure the error between each image and the centroid of the cluster it is assigned to. Both correpond to the error made when approximating the original image to either its projection or its cluster's centroid.
