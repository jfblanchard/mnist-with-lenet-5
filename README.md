# MNIST Classification with the LeNet-5 Architecture

LeNet-5 was created in 1998 by Yann Lacun, and was pioneering in its time for the performance. 
As the -5 in the name suggests, the architecture consists of 5 hidden layers; 3 convolutional layers and 2 fully connected layers. 
While very simple compared to newer architectures, it still performs at close to 99% accuracy with the MNIST dataset.  
<br>Other differences from modern architectures
are that it uses <b>tanh</b> as an activation function and <b>average pooling</b>, 
which have largely been replaced by <b>ReLU</b> and <b>max pooling</b> in recent times. 
Although nearly 25 years old, it may be of interest to those studying neural networks due to its historical significance.

This notebook implements the exact LeNet-5 architecture and learning rate scheduler as described in the original paper on the MNIST dataset using Keras. Portions of the code in this notebook are adapted from the notebook [here](https://github.com/moelgendy/deep_learning_for_vision_systems/blob/master/chapter_05/lenet_implementation_in_keras.ipynb).

The original paper is [here](http://yann.lecun.com/exdb/publis/pdf/lecun-01a.pdf)
