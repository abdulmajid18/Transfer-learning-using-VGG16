# Transfer-learning-using-VGG16

A pretrained network is a saved network that was previously
trained on a large dataset, typically on a large-scale image-classification task.

The VGG16 architecture, developed by Karen Simonyan and Andrew
Zisserman in 2014; it’s a simple and widely used convnet architecture for ImageNet.1

There are two ways to use a pretrained network: feature extraction and fine-tuning.
But feature extraction approach will be used
Feature extraction
Feature extraction consists of using the representations learned by a previous network
to extract interesting features from new samples. These features are then run through
a new classifier, which is trained from scratch.feature extraction consists of taking the convolutional base of a
previously trained network, running the new data through it, and training a new classifier
on top of the output..
