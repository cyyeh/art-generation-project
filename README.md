# Art Generation Using Neural Style Transfer

## Abstract

This technique which can generate a new image that mimics the content of an image A but mimics the style of an image B comes from [A Neural Algorithm of Artistic Style(Gatys et al.)](https://arxiv.org/abs/1508.06576).

## Introduction

This algorithm utilizes a pretrained convolutional neural network model called VGG19. With a pretrained convolutional neural network, we can directly access learned image features from intermediate layers of the network. This algorithm tries to solve the problem that we need to generate a new image that looks like image A but with the style of an image B. In order to do so, this algoirthm defines two cost functions, which is content cost function and style cost function. The total cost function is the weighted sum of the two cost functions.

## Related Information

According to TensorFlow tutorial, the modern approach to this problem is to train a model to generate the stylized image directly(similar to CycleGAN).