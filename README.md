# 541_CV_Project

## ASL Image Classification

## Authors: Bhavya Samhitha Mallineni (mallinen@usc.edu) and Dharitri Hemant Toshikhane (toshika@usc.edu)

#### Project Outline:
The goal of our Computer Vision ASL Project is to use image classification to classify the ASL alphabets. ResNet Convolutional Neural Network is utilized for the modeling process. The model will recognize the alphabet that an image represents when it is run through it, and it will generate an audio file that indicates which alphabet it is.

#### Stack:
1) Python
2) Pytorch
3) Google Colab
4) Github
   
#### Pre-Processing:
Resize to (224,224)
Normalization Mean = [0.485, 0.456, 0.406], Standard Deviation = [0.229, 0.224, 0.225]

#### Model Architecture:
1) ResNetr0
2) Optimizer: Adam
3) Criterion: Cross Entropy Loss
4) Learning rate: 0.001
5) Epochs: 5
6) Train Accuracy:99.18%
7) Validation Accuracy:99.65%
8) Test Accuracy: 96%

#### Models Implemented and Tried
1) ResNet50
2) ResNet101
3) ResNet152

#### Text to Speech module
We implemented Text to Speech using google Text-to-Speech, which converts the predicted image label to an audio and stored into a file.

#### Concluding Remarks
1) Extension: 
--We believe that this is just the first step as the application of Computer Vision in recognition of American Sign Language has wide scope for development. A few things which we believe that would help extend this project are to create Real Time video recognition system, with a lesser processing time. 
--Another application can be done by implementing sensors and actuators in gloves of the users and then interpret not only the alphabets but also sentences.

2) Questions that were answered
--We were excited to observe how the data was impacted by different types of ResNet models. 
--It was also learning to know how this model can be implemented in various real life situations now we can guess an alphabet easily with this model. 

3) Extended Curiosity
-- In real-world circumstances, hand gestures frequently occur at a high speed, necessitating models that can accurately represent rapid motions. We find the task of developing such a model and investigating the potential for real-time training intriguing, since it will push the frontiers of gesture detection in hectic and dynamic settings. How can we create and refine a model that smoothly responds to real-time, fast gestures, helping to herald in a new era of flexible and responsive human-computer interaction?

