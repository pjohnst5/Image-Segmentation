# Image-Segmentation
A machine learning approach to image segmentation

# Overview
This repo is a machine learning approach to segmenting images into multiple classes.  It includ 'Image-Segmentation.ipynb' contains a step by step walkthrough to the methods used and models tested to achieve segmentation results.

# Dataset
The dataset includes raw images of street views taken from cars with corresponding labeled images where each pixel of the labeled image has a value corresponding to which class that pixel belongs. For example, a cluster of pixels might all hold the value '11' to indicate that each of those pixels is part of a pedestrian. The images can be found in 'cityscapes_data.zip'. This datset has been cleaned from the original cityscapes dataset available at https://www.cityscapes-dataset.com/. The original dataset includes raw images, json files dictating the polygon outlines of objects, labeled images with just cars being labeled, and labeled images where every class is labeled. The 'cityscapes_data.zip' folder contains raw images with their corresponding labeled images where every class is labeled. 

# Code
See [ipynb file](Image_Segmentation.ipynb)
