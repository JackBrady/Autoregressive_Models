# Autoregressive Models
This repo is a Pytorch implementation of the autoregressive models assignment from Dr. Pieter Abbeel's CS 294-158 Deep Unsupervised Learning. 
The assignment description can be found in the included PDF.

The [Pixel-CNN](https://arxiv.org/abs/1601.06759) and [MADE](https://arxiv.org/abs/1502.03509) architectures were the primary focus of 
this project with the final model being a combination of the two. This model uses a Pixel-CNN to model dependencies between pixels, and a MADE to model dependencies between color channels, taking the Pixel-CNN's output as an auxillary input. The models were trained on color MNIST digits.

Samples from the original dataset as well as samples from the Pixel-CNN and Pixel-CNN-MADE can be seen below:

# Samples from Original Dataset

![figure 1](https://raw.github.com/JackBrady/Autoregressive_Models/master/MNIST_Samples.png)

# Samples from Pixel-CNN

![figure 1](https://raw.github.com/JackBrady/Autoregressive_Models/master/Pixel_CNN_Samples.png)

# Samples from Pixel-CNN-MADE

![figure 1](https://raw.github.com/JackBrady/Autoregressive_Models/master/Pixel_CNN_MADE_Samples.png)





