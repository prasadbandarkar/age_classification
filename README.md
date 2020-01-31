# Age Classification

This project aims to classify [frontal images of people](http://chalearnlap.cvc.uab.es/dataset/19/description/) according to their apparent ages using a convolutional neural network. The images of people over the age of 18 are considered and further separated into three roughly equal groups in the training data. Faces of these people are cropped out from the images using the Haar-cascade algorithm. These croppped faces are then used to train a convolutional neural network similar to a [LeNet-5 network](http://yann.lecun.com/exdb/lenet/). Validation is performed on a separate similar dataset.

Take a look at the PrepareFiles.ipynb notebook to check the image preprocessing performed before the training

ConvolutionalNetworks.ipynb notebook lists the details of the results of the convolutional neural network used to classify the faces
