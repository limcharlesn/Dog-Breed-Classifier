# Dog-Breed-Classifier

This project is part of Udacity's Deep Learning Nanodegree coursework.
This script uses a convolutional neural network (CNN) to identify human faces and dogs, and learns to classify dogs by their breeds and humans according to which dog breed they look like.

The initial architecture used in this script is inspired by the VGG16 model and uses 5 convolutional layers with max pooling and relu activation functions together with 3 fully connected layers with dropout and relu activation functions.

The training loss and validation loss after 100 training epochs are 2.913247 and 2.967499 respectively, and the test accuracy was 29%.

With transfer learning from the ResNet152 model, where only the last fully connected layer was redefined and retrained, a test accuracy of 85% was achieved after only 20 epochs of training.
