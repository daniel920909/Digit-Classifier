# DIGIT CLASSIFIER FOR REAL-WORLD IMAGES
In this project a Multilayer Perceptron neural network (MLP) and a Convolutional Neural Network (CNN) are built to classify digits from 0 to 9, from real-world images. For the project the SVHN dataset is used. This is an image dataset of over 600,000 digit images, obtained from house numbers in Google Street View images.

Data augmentation is used in the CNN in order to increase the accuracy of the model, taking into account important aspects. For instance, some images might contain more than one digit, and the image augmentation could affect the algorithm if operations such as horizontal shifts result in the labeled digit not being centered in the image.
