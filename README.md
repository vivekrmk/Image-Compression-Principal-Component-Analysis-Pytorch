# Image-Compression-Principal-Component-Analysis-Pytorch
In this tutorial we can use the Pytorchs efficient PCA implementation for performing data compression by retaining essential features of an Image. With the result of the PCA tensor, we also try to reconstruct the original Image.

Principal component Analysis aids towards meaningful inference of important features of data samples, especially when the given data set of samples is drawn from a homogenous population. Here we use PCA to project data into a lower dimension and also project it back to its original dimension. 

## Prerequisites 
Familiarity with topics in Linear Algebra such as matrix multiplication is a must, good to know concepts such as Singular value decomposition. Familiarity with Python will be needed.

## What it does
In this tutorial we can use the Pytorchs efficient PCA implementation for performing data compression by retaining essential features of an Image. After image compression, we will construct the original image back, Yes there will be some data loss when we reconstruct. We will visualize the newly constructed image after varying the compression parameter or number of principal components.
