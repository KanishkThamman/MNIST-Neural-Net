# MNIST Digit Classification using TensorFlow and Keras

This project demonstrates the process of building, training, and evaluating a neural network for the classification of handwritten digits from the MNIST dataset. The project covers data loading, preprocessing, model building, training, and evaluation.

## Requirements

To run this project, you need to have the following libraries installed:

- TensorFlow
- NumPy
- Matplotlib

You can install the required libraries using the following command:
``` pip install tensorflow numpy matplotlib ```


## Notebook Overview

### Data Loading and Exploration

- The MNIST dataset is loaded using `keras.datasets.mnist`.
- Training and testing data shapes are displayed.
- Sample images from the dataset are visualized.

### Data Preprocessing

- Images are flattened from 28x28 to 784-dimensional vectors.

### Model Building

- A simple neural network model is built using Keras.
- The model consists of an input layer with 784 neurons and an output layer with 10 neurons (for the 10 digit classes).
- Additional models with hidden layers are also built to observe the impact on performance.

### Model Compilation

- The model is compiled with the Adam optimizer and sparse categorical cross-entropy loss function.
- Accuracy is used as the evaluation metric.

### Model Training

- The model is trained on the training dataset for a specified number of epochs.

### Model Evaluation

- The trained model is evaluated on the test dataset to determine its accuracy.

### Experiments with Model Architecture

- Different model architectures are experimented with, including adding multiple hidden layers and changing activation functions.

## Key Code Snippets

1. Data Loading
2. Data Exploration
3. Data Preprocessing
4. Model Building and Compilation
5. Model Training
6. Model Evaluation
7. Experimenting with Hidden Layers

## Observations and Results

- The accuracy of the model improves with the addition of hidden layers.
- More complex models require more epochs to train effectively.
- A balance between the number of layers and the number of epochs is necessary to avoid diminishing returns.

## Conclusion

This project provides a comprehensive guide to building, training, and evaluating a neural network for digit classification using the MNIST dataset. Experimenting with different model architectures highlights the importance of model complexity and training duration in achieving high accuracy. Current accuracy is: 96% 

## License

This project is licensed under the MIT License