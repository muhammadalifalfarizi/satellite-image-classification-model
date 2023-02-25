# Dataset-Satelit-ML
--
Satellite Image Classification
This project aims to classify satellite images into different categories using machine learning techniques. The dataset used in this project is provided by XYZ Corporation and consists of satellite images of various regions around the world.
--
Dataset
The dataset consists of 10,000 satellite images of size 256x256 pixels. The images are labeled with one of 5 possible classes: Forest, Water, Urban, Agriculture, and Barren Land. The dataset is split into 80% training and 20% testing sets.
--
Methodology
In this project, we used a convolutional neural network (CNN) to classify the satellite images. The CNN was implemented using the Keras library in Python.

We first preprocessed the images by normalizing the pixel values and performing data augmentation (randomly rotating and flipping images). We then trained the CNN on the training set and evaluated its performance on the testing set.
--
Conclusion
In this project, we developed a CNN model to classify satellite images into different categories. The model achieved an accuracy of 85% on the testing set, with good precision and recall for each class. This project can be extended by using more advanced models or by incorporating additional data sources.
