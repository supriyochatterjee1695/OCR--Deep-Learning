# Deep Learning Project

### MNIST Digit Recognition using Tensorflow
The MNIST dataset is a widely used dataset in the field of machine learning. It consists of 28x28 grayscale images of handwritten digits (0 to 9) and their corresponding labels.


### Model Architecture
The digit recognition model is built using TensorFlow, a popular deep learning framework. The model architecture consists of the following layers:

Input Layer: Flattened 28x28 pixel image

Hidden Layers: Two fully connected hidden layers with ReLU activation functions

Output Layer: Fully connected output layer with 10 units (one for each digit)


### Model Training
1. Data Preprocessing: The pixel values of the images are normalized to the range [0, 1] and the labels are one-hot encoded.
2. Model Compilation: The model is compiled with appropriate loss function (categorical cross-entropy) and optimizer (Adam).
3. Model Training: The model is trained using the training data and validated using the validation data.
4. Model Evaluation: The accuracy of the trained model is evaluated using the test data.

### Acknowledgements
The MNIST dataset is sourced from the TensorFlow datasets module. This project is intended for educational purposes and to showcase the implementation of a digit recognition model using TensorFlow.
