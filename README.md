# Deep learning for pneumonia detection based on chest X-rays
In this project a convolutional neural network is built and trained from scratch to detect pneumonia from chest X-ray images.
A link with a dataset that was used to train and test the network is given below:

https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia

This dataset contains 3 classes of X-ray images: bacterial pneumonia, viral pneumonia and normal (non-sick patients).
Since the dataset is imbalanced, the majority class is undersampled in order to create a balanced dataset.

This CNN is able to classify the X-ray images into one of the three classes with a validation accuracy of 86% and test accuracy of 70%.
