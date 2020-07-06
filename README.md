# Understanding-PCA
This repository is a summary giving a full  understanding for selecting the number of principal components for PCA. I simple way is to see a ratio of lambda values where we have 95-99% information/variance is retained. Use the cumulative sum of the Eigen values you get from the covariance matrix.Look into the notebook you will be clear.
A point to understand in the weight vector is that we transposed the weight vector by using **reshape(4,1)** and then multiplied it with X_std to obtain Y
