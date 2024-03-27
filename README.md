# DS_Hw10

These two code snippets are implementations of Convolutional Neural Networks (CNNs) for image classification tasks using the Fashion MNIST dataset. Here's what each code does:

1. The first code snippet:
   - Imports necessary libraries like NumPy for numerical computations, Keras for building and training neural networks, and Matplotlib for visualization.
   - Loads the Fashion MNIST dataset and preprocesses it by expanding dimensions and normalizing the pixel values to the range [0, 1].
   - Defines a function `train_cnn_model` to create, compile, train, and evaluate CNN models with different configurations.
   - Specifies different configurations for CNN models in the `configs` list.
   - Iterates over each configuration, builds a CNN model accordingly, trains it on the training data, and stores the training history for visualization.
   - Visualizes the training and validation accuracy for each configuration using Matplotlib.

2. The second code snippet:
   - Imports necessary libraries similar to the first snippet.
   - Loads the Fashion MNIST dataset and preprocesses it by normalizing the pixel values and expanding dimensions.
   - Constructs a simple CNN model using Keras Sequential API with two convolutional layers, max pooling layers, and dense layers.
   - Compiles the model with the Adam optimizer and sparse categorical cross-entropy loss.
   - Trains the model on the training data for 10 epochs and evaluates its performance on the test data.
   - Prints the test accuracy of the trained model.

Overall, both codes are used to train CNN models on the Fashion MNIST dataset to classify fashion-related images into different categories, and they demonstrate different approaches to defining and training CNN architectures using Keras.
