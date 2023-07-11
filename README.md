# Assignment 3 - Part 2

This repository contains the code for Assignment 3 - Part 2. The goal of this task is to use at least two pretrained CNN models to identify the type of a flower appearing in an image. The chosen pretrained models for this task are YOLOv5 and VGG19.

## Code Repository
To access the code for this task, please follow this link: [Code Repository](https://github.com/orisimh/Ass3_Part2)

## Task Description
The task involves transfer learning using two pretrained CNN models to classify flower images into their corresponding categories. The objective is to identify the type of flower in an image, specifically focusing on the dandelions category in this example.

## Deep Learning Packages
The code is implemented using the Keras/TensorFlow deep-learning package. This package provides a high-level API for building and training neural networks.

## Pretrained Models
For this task, two pretrained models, YOLOv5 and VGG19, have been chosen. These models will be adapted and fine-tuned to the current flower classification task. Additionally, other pretrained models may be used to enhance the performance of the classification.

## Dataset
The image database used for training and testing is provided in the following link: [Flower Image Database](https://www.robots.ox.ac.uk/~vgg/data/flowers/102/). This database contains a collection of flower images categorized into 102 classes.

## Model Output and Probability
The trained models will classify the flower images into their respective categories. The models will provide a probabilistic output, indicating the probability of a flower belonging to each of the categories.

## Instructions
To run the code and perform the flower classification task, follow these steps:

1. Clone the repository or download the code locally.
2. Ensure that the necessary dependencies and libraries are installed (Keras, TensorFlow, etc.).
3. Prepare the flower image dataset by downloading it from the provided link.
4. Adapt and fine-tune the YOLOv5 and VGG19 models for the flower classification task.
5. Train the models on the flower dataset.
6. Test the models on a separate validation or test dataset to evaluate their performance.
7. Analyze the results and interpret the probabilities of flower categories predicted by the models.
