# Pizza Recognition CNN

This CNN is trained to recognize pizza in .jpg images. Given an input image, the model will output a prediction of whether or not the image contains a pizza.

## Model Architecture

This model consists of several convolutional and max pooling layers followed by a fully connected layer with three linear layers. The first layer is a 2D convolutional layer with 3 input channels and 64 output channels, followed by batch normalization, a ReLU activation function, and a max pooling layer. The model then has three more similar blocks of convolutional, batch normalization, ReLU, and max pooling layers, each with an increasing number of output channels. The final block also includes a second convolutional layer. The fully connected layer has three linear layers with ReLU activation functions in between, and the final linear layer has an output size of 2.

## Training

The model was trained on a dataset of images of pizzas and non-pizzas. The model was optimized using the binary cross-entropy loss function and the Adam optimization algorithm.

## Evaluation

The model was evaluated on a hold-out test set and achieved an accuracy of 84%. This means that the model correctly identified whether or not an image contained a pizza 84% of the time.

## Usage

To use the model, input a .jpg image into the model and the model will output a prediction of whether or not the image contains a pizza.

