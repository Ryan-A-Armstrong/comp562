# Introduction to Computer Science (UNC COMP 592) Project

## Abstract

Previous work has has applied deep learning methods to classify pneumonia in chest x-rays. These methods rely on training and testing on quality x-ray images. However, approximately 5% of chest x-rays experience an augmentation that requires image retake for diagnosis, doubling patient radiation exposure. Using a convolutional neural network (CNN) architecture based on state of the art pneumonia detectors, we quantify the effects of clinically relevant augmentations to investigate if CNNs can be used to limit image retake. Notably, we found a CNN only trained on clean images is not robust to imaging issues, however, it retains accuracy to a larger degree in augmentations that humans are poor at reading (such as blurring effects) than in augmentations humans are better at reading (such as underexposure), indicating possible motivation to further explore the use of CNNs to detect pneumonia in these areas.

## Group Members

Vikram Aikat, Ryan Armstrong, Rohan Arora, Sam Nielsen

## Report
[Read the report here](comp562pneumonia.pdf)

## Dataset

Download the kaggle set: https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia/data#

Keep the test, train and val folders at the same level as the notebook. 
