# DNN-Digit-Classifier
- Using the **MNIST dataset**, imported from *Keras*, we train the model with 60,000 samples of handwritten digits and test it with another 10,000 samples for ensuring it's accuracy.
 
  ![alt text](https://github.com/n5hossai/DNN-Digit-Classifier/blob/main/numbers.png)
- At first, we divide the dataset into a training and test dataset
- Then we normalize both the training and test dataset using keras normalize function(where axis is considered 1). This is done to make sure that any change in color, does not violate the parameters for the following functions
- Using the reshape function from the *numpy* library, we increase the dimension for the kernel operation
- Sequential model and the following layers are being imported from *Keras*:
  * Dense
  * Dropout
  * Activation
  * Flatten
  * Conv2D
  * MaxPooling2D
- Then, we create three convolutional layers, using *relu* as the activation function and then flatten it from a 2D to 1D
- Three more connected layers are used, from which the first two use *relu* as the activation function, while the last uses *softmax* since we are trying to classify the output layers into 10 classes

- Training the model

  ![alt text](https://github.com/n5hossai/DNN-Digit-Classifier/blob/main/traingss.png)


- Then we use numpy to understand our prediction 
