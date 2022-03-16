[//]: # "Image References"
[image1]: ./images/sample_dog_output.png "Sample Output"
[image2]: ./images/vgg16_model.png "VGG-16 Model Layers"
[image3]: ./images/vgg16_model_draw.png "VGG16 Model Figure"

## Project Overview

This a Convolutional Neural Networks (CNN) built through the Udacity Deeplearning Nanodegree! In this project, I built a pipeline that can be used within a web or mobile app to process real-world, user-supplied images. Given an image of a dog, the algorithm will identify an estimate of the canine’s breed. If supplied an image of a human, the code will identify the resembling dog breed.

### Instructions

1. The model is defined in the dog_app.ipynb file. It includes the use of a prebuilt model, custom model from scratch, and a model using transfer learning.
2. The custom CNN will be saved in "model.pt"
3. The CNN using transfer learning will be saved in "model_transfer.pt"
4. Images are in for humans should be added to a folder called `lfw` and can be downloaded from (here)[https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/lfw.zip]
5. Images for dogs used for training should be added to a folder called `dogImages` and can be downloaded from (here)[https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip]
