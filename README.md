# MNIST

## MNIST-Convolutional-Neural-Networks.ipynb

Utilized concept of Deep Learning and convolutional neural networks and on the MNIST data to classify images.
The Code is written in Python using Keras, which is a Deep Learning library for Python.

The following concepts have been used :
i) KerasClassifier : wrapper which is an Implementation of the scikit-learn classifier API for Keras

ii)  fit_generator :  fits the model on batches with real-time data augmentation

iii) ImageDataGenerator : 
       * configure random transformations and normalization operations to be done on your image data during training
       * instantiate generators of augmented image batches (and their labels) via .flow(data, labels) or .flow_from_directory(directory). 
         These generators can then be used with the Keras model methods that accept data generators as inputs, fit_generator, 
         evaluate_generator and predict_generator.
         
iv) flow(x, y): Takes numpy data & label arrays, and generates batches of randomly transformed augmented/normalized images. Yields batches indefinitely, in an infinite loop.

For Reference : https://blog.keras.io/building-powerful-image-classification-models-using-very-little-data.html

Achieved a Test Accuracy of 0.9939

![image](https://user-images.githubusercontent.com/9651206/34577626-a6c84e54-f136-11e7-9978-f6adad0b4450.png)


