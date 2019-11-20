# Autoregressive Models
This repo is a PyTorch implementation of the autoregressive models assignment from Dr. Pieter Abbeel's CS 294-158 Deep Unsupervised Learning. 
The assignment description can be found in the included PDF.

The [PixelCNN](https://arxiv.org/abs/1601.06759) and [MADE](https://arxiv.org/abs/1502.03509) architectures were the primary focus of 
this project with the final model being a combination of the two. This model uses a PixelCNN to model dependencies between pixels, and a MADE to model dependencies between color channels, taking the PixelCNN's output as an auxillary input. The models were trained on color MNIST digits.

Samples from the original dataset as well as samples from the PixelCNN and PixelCNN-MADE can be seen below:

# Samples from Original Dataset

![figure 1](https://raw.github.com/JackBrady/Autoregressive_Models/master/Samples/MNIST_Samples.png)

# Samples from PixelCNN

![figure 1](https://raw.github.com/JackBrady/Autoregressive_Models/master/Samples/Pixel_CNN_Samples.png)

# Samples from PixelCNN-MADE

![figure 1](https://raw.github.com/JackBrady/Autoregressive_Models/master/Samples/Pixel_CNN_MADE_Samples.png)





