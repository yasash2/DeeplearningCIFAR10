# DeeplearningCIFAR10
CIFAR10 dataset modelling using deep learning
The CIFAR-10 dataset consists of 60000 32x32 colour images in 10 classes, with 6000 images per class. There are 50000 training images and 10000 test images.

The dataset is divided into five training batches and one test batch, each with 10000 images. The test batch contains exactly 1000 randomly-selected images from each class. 
The training batches contain the remaining images in random order, but some training batches may contain more images from one class than another. Between them, the training 
batches contain exactly 5000 images from each class.

The classes present in the above dataset are : 
1) Airplane
2) Automobile
3) Bird
4) Cat
5) Deer
6) Dog
7) Frog
8) Horse
9) Ship
10) Truck

The classes are completely mutually exclusive. There is no overlap between automobiles and trucks. "Automobile" includes sedans, SUVs, things of that sort. "Truck" includes
only big trucks. Neither includes pickup trucks.

This covers the information about the dataset.
In the project, one convolutional neural network is created, named 'cnn'. For any image, the processing of images should be done only after :
1) Convolution 
2) Pooling

These 2 methods help the computer to understand the features present in an image more clearly, and thus we get imporved results.

Required packages :
1. Numpy
2. Keras
3. Sklearn
