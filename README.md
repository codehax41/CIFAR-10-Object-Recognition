# CIFAR-10-Object-Recognition
CIFAR-10 is an established computer-vision dataset used for object recognition. It is a subset of the 80 million tiny images dataset and consists of 60,000 32x32
Models compared

Wide Residual Network
ResNet
VGG
Papers referred

Very Deep Convolutional Networks For Large-Scale Image Recognition
Deep Residual Learning for Image Recognition
Wide Residual Networks
INSTALLATION OF REQUIRED TOOLS
1. Tensorflow
Refer to the following link https://www.tensorflow.org/install/install_sources. Tensorflow is used as backend for Keras. The link contains installation instructions with and without gpu support

2. Keras
Keras is a high-level neural networks API, written in Python and capable of running on top of TensorFlow, CNTK, or Theano. It was developed with a focus on enabling fast experimentation.


3. Matplotlib
Matplotlib is a Python 2D plotting library which produces publication quality figures in a variety of hardcopy formats and interactive environments across platforms.

4.Skimage
Scikit-image is an image processing toolbox for SciPy. It is used for loading,saving and applying various transformations like color to gray and gray to color on images.

5. graphviz
This package facilitates the creation and rendering of graph descriptions in the DOT language of the Graphviz graph drawing software from Python. It is required to plot the models in keras.

To install graphviz

sudo pip install graphviz

6. Jupyter Notebook
The Jupyter Notebook is an open-source web application that allows you to create and share documents that contain live code, equations, visualizations and narrative text


It opens up all the notebooks which are there in the directory in the browser.

ResNet and Wide residual models have been trained from scratch
VGG is trained with the help of transfer learning. Here the models weights are initialised with ones obtained from training on ImageNet
All the hyperparameters are kept constant for all the models while training.
Comparison of Various Models
Summary
The difference between the time taken by the VGG to train with and without transfer learning is huge.
Wide residual networks gives better results in lesser time compared to ResNet.
And proved that with the help of Simple CNN we can achieve good results with proper hyper parameter tuning and regularization techniques.
WRN-16-10 Performance  

ResNet-50 Performance  

ResNet50 vs WRN-16-10  
