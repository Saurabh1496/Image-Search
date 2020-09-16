# Image-Search
It is a simple application that utilizes **Convolutional AutoEncoder** for extracting latent features by doing **unsupervised** training on CIFAR-10 dataset. After the Images are transformed using the Encoder part of ConvAutoEncoder into **512-D** vector, ANN is used to find similar images as the given one. The Code for extracting features is inside **CIFAR_CAE.ipynb** that will save the trained model as **ConvAutoEncoder.h5**. Code for similar image-search using ANN is inside **ImageSearch**. Pre-trained is provided in the repo, choose to use that or else train your own model by changing hyperparameters.

## Dependencies
  * [Keras](https://keras.io/)
  * [Numpy](http://www.numpy.org/)
  * [Matplotlib](https://matplotlib.org/)
  * [Annoy](https://pypi.org/project/annoy/1.0.3/)

## Architecture
![Convolutional AutoEncoder Architecture](/image/arch.png "Convolutional AutoEncoder Architecture")
