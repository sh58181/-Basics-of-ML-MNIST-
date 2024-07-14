# -Basics-of-ML-MNIST-
This code trains and evaluates a Convolutional Neural Network (CNN) on the MNIST dataset of handwritten digits.

1. Data Preparation:
   - Loads the MNIST dataset.
   - Transforms the images to tensor format.
   - Creates data loaders for batch processing during training and testing.

2. Model Definition:
   - Defines a CNN architecture with convolutional, dropout, and fully connected layers.
   - Implements the forward pass through the network.

3. Training:
   - Initializes the model, loss function (cross-entropy), and optimizer (Adam).
   - Trains the model over multiple epochs, updating weights based on the loss.

4. Evaluation:
   - Evaluates the model on the test dataset after each epoch.
   - Prints out the training progress and performance metrics (loss and accuracy) during training and testing.

