# image_colorization
Taking a batch of black and white images and colorizing them using a U-Net CNN.

# Project Objective
This project creates a model that can be fed a black and white image, and output a colored image. This project uses a pseudo-supervised pipeline that transforms a raw image into black and white, then treats them as input-output pairs. 

# Enironment
-CUDA 12.0 
-Python 3.8.10 
-Jupyter Notebook

# Data
The dataset for this project comes from the CIFAR-10 dataset, containing 60,000 color images grouped into 10 classes with roughly 6,000 images per class. The data is split into 50,000 training images and 10,000 test images. The full dataset can be found at https://www.cs.toronto.edu/~kriz/cifar.html.

# Model
U-Net Convolutional Neural Network

# Model Training
![Training Metrics](images/Training_metrics.jpg)
Following 100 epochs, the training and validation loss metrics are graphed to show the performance of the model. 

# Model Evaluation
![Output Samples](images/Output.jpg)
