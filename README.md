[//]: # (Image References)

[image1]: ./images/sample_dog_output.png "Sample Output"
[image2]: ./images/vgg16_model.png "VGG-16 Model Keras Layers"
[image3]: ./images/vgg16_model_draw.png "VGG16 Model Figure"


## Project Overview

This project was required as part of the Artificial Intelligence Nanodgree which I completed in April. The main task was to build a Convolutional Neural Network Classifier for classifying a picture in one of 133 possible dog breeds. 


![Sample Output][image1]




## Project Description

### Instructions

The project consists of 2 parts.

1) Building a model from scatch and train it based on ~ 6000 training photos (and achieving 1% accuracy)
2) Building a transfer learning model using different pretrained network (i.e VGG-19, Inception, Exception, ResNet-50) (and achieving 60% accuracy


## Project Achievements

1) By using Dropout and Batch Normalization, in addition to several network layers, the accuracy of 30% was achieved (compared to project requirements of 1%)
2) I experimented with all the different pretrained models instead of just 1 required and achieved accuracy of 85%, compared to required 60%
3) By using Bagging techniques I increased the final accuracy to 87%
4) When testing the results I found that my dog which I always thought was a mix of labrador and another breed was identified as a Beuceron and when I looked up the pictures of the Beuceron breed I was previously unfamiliar with. My dog indeed resembled it the most!
