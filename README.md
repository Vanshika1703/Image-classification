# Image Classification Using TensorFlow 🌸  
This project implements an image classification model to categorize flower images into five distinct classes: daisy, dandelion, roses, sunflowers, and tulips. The project uses TensorFlow and Keras to preprocess the dataset, build the model, and evaluate its performance.

## Project Overview   
The goal of this project is to classify images of flowers into one of five categories using a Convolutional Neural Network (CNN). The model achieves this by:

1.Preprocessing image data using rescaling and data augmentation.  
2.Training a CNN with layers for convolution, pooling, and dropout to improve generalization.  
3.Evaluating performance using validation accuracy and loss metrics.  

## Technologies Used  
Programming Language: Python  
Framework: TensorFlow 2.x, Keras  
Libraries:  
Data Handling: NumPy, Pandas  
Visualization: Matplotlib  

## Dataset  
The dataset consists of 3,670 flower images sourced from TensorFlow's sample datasets.
[dataset link](https://storage.googleapis.com/download.tensorflow.org/example_images/flower_photos.tgz)

Classes: Daisy, Dandelion, Roses, Sunflowers, Tulips  
Data Split:
80% for training
20% for validation   

## Training Results  
The model was trained for 15 epochs. Key metrics:

Training Accuracy: Up to 99%  
Validation Accuracy: 70%  
Loss Trends: Validation loss stabilized with data augmentation and dropout.
