# Object Recognition
_Computer Vision Project - Universidad Politécnica de Madrid.  
Feed-Forward Neural Network and Convolutional Neural Network in Tensorflow._

# Overview
The aim of this work is to solve several computer vision problems using deep models:  
• Develop proficiency in using Keras for training and testing neural nets (NNs).  
• Optimize the parameters and architectures of a dense feed-forward neural network (ffNN), and a convolutional neural net (CNN) for image classification.  
• Build a traffic sign detection algorithm.

In this paper, an analysis of the German Traffic Sign Benchmark and CIFAR 100 datasets are performed with applying different methodologies in the spectrum of Computer Vision. Starting from the most basic architectures and gradually improving the algorithm. From Feed-Forward Neural Network to Convolutional Neural Network. Lastly, an object detection and recognition algorithm is build and evaluated. This work has been development in TensorFlow.

The first dataset is the German Traffic Signs Recognition Benchmark. It consist of 43 classes corresponding to street signs in Germany. The number of images in each class vary from 210 to 2250. The images are in a PPM format of varying sizes from 15x15 pixels to 250x350 pixels. The shape is not necessarily squared. The images include some space between boundaries and the actual sign so that edge based approaches can be used. The annotation corresponding to an image is provided as the class of the sign present in the image and relative coordinates of the bounding box enclosing the street sign.  
 The second dataset is the CIFAR 100 Dataset. It has 100 classes and each image consists of 3 RGB colour channels and 32x32 pixel dimensions for an overall size per input of 3x32x32 = 3072.  
Download the full data sets from http://benchmark.ini.rub.de/?section=gtsdb&subsection=dataset

# Repository Content
- Results and Discussion - _Computer Vision final report.pdf_
- Python script of the ffNN part - _ffNN.ipynb_
- Python script of the CNN part - _CNN.ipynb_
- Python script of the object detection part - _object_detection.ipynb_

![CNN 3th_2](https://user-images.githubusercontent.com/55877748/89284153-a3ac6980-d64e-11ea-93a9-f920c1c92724.png)
