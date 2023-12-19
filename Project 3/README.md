# CS672 Deep Learning Project #3

Build a Deep Learning model (based on Neural Networks) that provides reliable and improved accuracy of an Image Recognition Classifier based on Convolution Neural Networks (CNNs).

For comparing and contrasting, device two (2) CNNs models, on two (2) distinct Deep Learning frameworks!

<<< A >>> Implementing TensorFlow code

1. A Keras Sequential model with multiple Convolution and MaxPooling layers, and
2. Make use of a pre-trained model

Establish a ‘base’ model by creating a ‘home-grown’ image classifier, for example:

For the second, pre-trained CNNs model, use the very powerful image recognition classifier InceptionV3 model. Download the pre-trained model (inception_v3_weights.h5) from the Classes portal.

Note: H5 is a file format to store structured data, it's not a model by itself. Keras saves models in this format as it can easily store the weights and model configuration in a single file.

Both of these models should be trained and validated on the ‘Kaggle Cats and Dogs Dataset’. Download the data using this link: https://www.microsoft.com/en-us/download/confirmation.aspx?id=54765

The directory structure of the training and validation datasets should look like the following:

Details about the IncerptionV3 pre-trained model and configuring new layers/weights, within TensorFlow review the following blog: https://www.tensorflow.org/api_docs/python/tf/keras/applications/inception_v3/InceptionV3

Similarly, to TensorFlow’s modeling and transfer learning tasks, perform activities within PyTorch framework.

<<< B >>> Implementing PyTorch code

<<< C >>> Compare the results, performance by applying Transfer Learning within TensorFlow vs PyTorch.