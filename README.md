# ConvNet-TF-CIFAR10

Classify images from the CIFAR-10 dataset. The dataset consists of airplanes, dogs, cats, and other objects. The dataset is preprocessed, then trained a convolutional neural network on all the samples. I normalized the images, one-hot encode the labels, build a convolutional layer, max pool layer, and fully connected layer.<br>

Final architecture: 3 Conv+Maxpool layers, 3 full connected layers, 5 drop out layers. Training on 200 epochs on a Floyd GPU achieved 71% testing accuracy.<br>

Part of the Udacity Deep Learning Foundations Nanodegree.
