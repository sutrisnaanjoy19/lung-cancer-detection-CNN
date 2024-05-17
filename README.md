# Lung Cancer Detection with CNN

This thesis claims to detect nodules and its position from the 3d CT scan images

Objective of this thesis is to maximize the accuracy and reduction of false positive cases (databases used are LUNA-16 and LIDC-IDRI dataset).

In Preprocessing segmentation thresholding or watershed segmentation is used, in this thesis I tried to implement deep learning architectures like U-Net, ResNet, AlexNet and different modified 3D-CNN versions. Libraries used are Keras, Pandas, Numpy, Tensorflow, OpenCV, Scikit-Image.

Loss and the Activation function used are Binary Cross-entropy or log loss, ReLu in the hidden layer and Softmax in the output layer.
