# MNIST Image Classification using Artificial Neural Network (ANN) (99% ACCURACY)

Handwritten Digit Recognition Model GOT 99.01% Accuracy on the test set using JUST Artificial Neural Network (ANN) WITHOUT CNN.

## Dataset

The MNIST dataset consists of 28x28 grayscale images of handwritten digits (0-9). The dataset is split into a training set of 60,000 images and a test set of 10,000 images.

![image](https://github.com/SaadElDine/MNIST-Using-Artificial-Neural-Network-ANN/assets/113860522/a9c2cd7e-a22d-4783-9059-1486926c02d7)


## Model Architecture

The ANN model is implemented using TensorFlow and Keras. It consists of five dense layers with ReLU activation functions. The output layer uses a softmax activation function to output probabilities for each digit class.

- Input Layer (Flatten): 784 nodes
- Hidden Layer 1: 512 nodes, ReLU activation
- Hidden Layer 2: 256 nodes, ReLU activation
- Hidden Layer 3: 128 nodes, ReLU activation
- Hidden Layer 4: 64 nodes, ReLU activation
- Output Layer: 10 nodes (one for each digit), softmax activation

## Training

The model is trained using the Adam optimizer and Categorical Crossentropy loss function. Batch normalization is applied after each hidden layer to improve training stability and performance. The training process uses early stopping to prevent overfitting.

## Data Augmentation

Data augmentation is applied to the training set using the `ImageDataGenerator` class from Keras. Augmentation techniques include rotation, width and height shifts, shear, zoom, and horizontal flipping. This helps the model generalize better to unseen data and improve accuracy.

## Evaluation

The model is evaluated on the test set using the `evaluate` method. The accuracy achieved on the test set is 99%.
![image](https://github.com/SaadElDine/MNIST-Using-Artificial-Neural-Network-ANN/assets/113860522/478933bd-bfe7-4cb9-9153-f91fa4611b43)


## Prediction

The model can be used to make predictions on new images. Users can upload an image of a handwritten digit, and the model will predict the digit using the uploaded image.
![image](https://github.com/SaadElDine/MNIST-Using-Artificial-Neural-Network-ANN/assets/113860522/209f94d7-ddee-4ee2-bb80-e5163bdb1c43)


## You Can Try It For Free!
![image](https://github.com/SaadElDine/MNIST-Using-Artificial-Neural-Network-ANN/assets/113860522/f8fd5d2f-6552-4e87-9de3-08e098854bce)






