# Image-Search
It is a simple applicatoin that utilizes **Convolutional AutoEncoder** for extracting latent features by doing **unsupervised** training on CIFAR-10 dataset. Code for this part is inside **CIFAR_CAE.ipynb** that will save the trained model as **ConvAutoEncoder.h5**. Pre-trained is provided in the repo, choose to use that or else train your own model by changing hyperparamters.

## Architecture
Image of AutoEncoder


## Using Approximate Nearest Neighbors (ANN)
After the Images are transformed using Encoder part of ConvAutoEncoder into **512-D** vector, ANN is used to find similar images as the given one.