# Overview

This project is focused on reading in images, manipulating and displaying them using Python libraries such as Pandas, NumPy, OpenCV, and Matplotlib.

# Dataset:

The dataset can be downloaded here: **https://www.kaggle.com/datasets/tongpython/cat-and-dog**.

# How to Import
To use the project, the following libraries should be imported:

* `pandas (as pd)`;
* `numpy (as np)`;
* `glob`;
* `cv2`;
* `matplotlib.pylab (as plt);`;

# Reading in Images

The project reads in cat and dog images using the glob module which returns a list of file paths. Two lists are created, one for cat images and the other for dog images. An image from the cat list is selected and displayed using both OpenCV and Matplotlib libraries. The image dimensions are displayed using the .shape method.

# Image Array

The image is converted into an array and plotted as a histogram to show the distribution of pixel values.

# Display Images

The selected cat image is displayed using Matplotlib with the imshow() and axis() methods.

# Image Channels

An RGB image has three channels: red, green, and blue. These channels are extracted and displayed separately using Matplotlib.

# Matplotlib vs cv2 Numpy Arrays

There is a difference between the way OpenCV reads in images and the way Matplotlib does. The project shows how to convert images from the OpenCV format (BGR) to the Matplotlib format (RGB) using the cvtColor() method.

# Image Manipulation

The project demonstrates how to manipulate images using OpenCV. A dog image is read in and converted to grayscale. The grayscale image is then displayed.

# Resizing and Scaling

The project shows how to resize an image using OpenCV. Two methods are used: resize() and filter2D(). The former is used to reduce the size of the image while the latter is used to sharpen and blur the image.

# CV2 Kernels

The project uses filter2D() to apply sharpening and blurring kernels to the dog image.

# Save Image

The project demonstrates how to save an image using both Matplotlib and OpenCV.
