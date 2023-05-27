# Satellite Image Classification Model

This repository contains a deep learning model for satellite image classification. The model is trained to classify satellite images into four categories: cloudy, desert, green area, and water.

### Dataset

The model is trained on a dataset of satellite images, which can be downloaded from the following Kaggle dataset:

### Satellite Image Classification Dataset

The dataset consists of images in different categories, each representing a specific type of land cover.

### Model Architecture

The model architecture is a convolutional neural network (CNN) built using the Keras Sequential API. It consists of several convolutional layers followed by max-pooling layers, a flatten layer, and dense layers. The final dense layer uses softmax activation to output the predicted probabilities for each class.

The model architecture summary can be found in the code file.

### Training

The model is trained using the TensorFlow framework. The training process involves data preprocessing, including image resizing, normalization, and augmentation. The training data is split into training and validation subsets.

During training, a custom callback is used to monitor the accuracy on both the training and validation data. If the accuracy reaches 88% on both sets, the training process is stopped early.

The training history, including accuracy and loss curves, is visualized using matplotlib.

### Inference

Once the model is trained, it can be used for making predictions on new satellite images. The predict function takes an image as input, preprocesses it, and returns the predicted class label.

An example image and its predicted class are included in the code file.

### TensorFlow Lite Conversion

The trained model is also converted to TensorFlow Lite format for deployment on resource-constrained devices. The TensorFlow Lite model can be used in mobile and embedded applications.

The converted model is saved as model.tflite.

Feel free to customize and extend this model according to your needs. Enjoy exploring satellite image classification with deep learning!
