# Cat-vs-Dog-Predictor-Model
In this project i construct a CNN model in which i used thousands of images of cats and dogs for training and testing.
Image Classification is one of the most interesting and useful applications of Deep neural networks and Convolutional Neural Networks that enables us to automate the task of assembling similar images and arranging data without the supervision of real humans.
The libraries we will using are : 
Pandas – This library is used to load 2D array format and DataFrames.
Numpy – It is used to perform large computations in a very short time.
Matplotlib – This library is used to draw visualizations.
Sklearn – This module contains multiple libraries having pre-implemented functions to perform tasks from data preprocessing to model development and evaluation.
OpenCV – This is an open-source library mainly focused on image processing and handling.
Tensorflow – This is an open-source library that is used for Machine Learning and Artificial intelligence and provides a range of functions to achieve complex functionalities with single lines of code.
Model Architecture(The model will contain the following Layers):
Four Convolutional Layers followed by MaxPooling Layers.
The Flatten layer to flatten the output of the convolutional layer.
Then we will have three fully connected layers followed by the output of the flattened layer.
We have included some BatchNormalization layers to enable stable and fast training and a Dropout layer before the final layer to avoid any possibility of overfitting.
The final layer is the output layer which has the activation function sigmoid to classify the results into two classes.
