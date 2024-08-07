# Image-Segmentation-of-Handwritten-Digits

In this repo, I develop a model that predicts segmentation masks (pixel-wise label maps) of handwritten digits. The model is trained on the M2NIST dataset, a multi-digit extension of MNIST.

![multi-digit-mnist](./results/01-multi-digit-mnist.png)

# The Model

I construct a Convolutional Neural Network (CNN) from scratch for the downsampling path and use a Fully Convolutional Network (FCN-8) to upsample and produce the pixel-wise label maps. 

![model-fcn8](./results/02-model-fcn8.png)

# Segmentation Results

The model's performance is evaluated using Intersection over Union (IOU) and Dice Score metrics.

![seg-results](03-seg-results.png)
