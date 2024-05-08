# Convolutional Autoencoder for Image Denoising

## AIM

To develop a convolutional autoencoder for image denoising application.

## Problem Statement and Dataset
Autoencoder is an unsupervised artificial neural network that is trained to copy its input to output. An autoencoder will first encode the image into a lower-dimensional representation, then decodes the representation back to the image.The goal of an autoencoder is to get an output that is identical to the input. Autoencoders uses MaxPooling, convolutional and upsampling layers to denoise the image. We are using MNIST Dataset for this experiment. The MNIST dataset is a collection of handwritten digits. The task is to classify a given image of a handwritten digit into one of 10 classes representing integer values from 0 to 9, inclusively. The dataset has a collection of 60,000 handwrittend digits of size 28 X 28. Here we build a convolutional neural network model that is able to classify to it's appropriate numerical value.

![image](https://github.com/pavizhi/convolutional-denoising-autoencoder/assets/95067176/89f96e37-c189-44d0-9a47-bb3d0d417925)

## Convolution Autoencoder Network Model

![image](https://github.com/pavizhi/convolutional-denoising-autoencoder/assets/95067176/24a49e84-359d-40ac-bc0f-04ef515ded64)


## DESIGN STEPS

### STEP 1:
Import the necessary libraries and load the mnist dataset without label column (y).
### STEP 2:
Scale the input (gray scale) images between 0 to 1.
### STEP 3:
Add noise to the input image and scale the noised image between 0 and 1.
### STEP 4:
Build the Neural Network model with
<ol>
  <li>Encoder</li>
<ul>
  <li>Convolutional layer</li>
  <li>Max Pooling (downsampling) layer</li>
</ul>
  <li>Decoder</li>
  <ul>
    <li>Convolutional layer</li>
    <li>Upsampling layer</li>
  </ul>
</ol>

### STEP 5:
Compile and fit the model.
### STEP 6:
Plot the predictions.

## PROGRAM

Include your code here

## OUTPUT

### Training Loss, Validation Loss Vs Iteration Plot

Include your plot here

### Original vs Noisy Vs Reconstructed Image

Include a few sample images here.



## RESULT
