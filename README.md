# Traffic_sign_classify

This Python project , is build on a deep neural network model that can classify traffic signs present in the image into different categories. 
With this model, we are able to read and understand traffic signs which are a very important task for all autonomous vehicles.
For this project, uses the public dataset available at Kaggle. To classify the images into their respective categories, we will build a CNN 
model (Convolutional Neural Network). CNN is best for image classification purposes.

### Prerequisites

This project requires prior knowledge of Keras, Matplotlib, Scikit-learn, Pandas, PIL and image classification.

### Traffic Signs Classifier GUI

Tkinter is a GUI toolkit in the standard python library, which is used for a graphical user interface for our traffic signs classifier
In this file, I have first loaded the trained model ‘traffic_classifier.h5’ using Keras. 
And then there is the GUI for uploading the image and a button is used to classify which calls the classify() function.

### Summary

In this Python project with source code, we have successfully classified the traffic signs classifier with 95% accuracy and also visualized 
how our accuracy and loss changes with time, which is pretty good from a simple CNN model.
