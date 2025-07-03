# Image Classification Using Teachable Machine and Colab
A simple image classification project using Teachable Machine and Google Colab.The model was trained to recognize two classes: Car and Racing Bike.
This project shows how to create a image classification model using Google Teachable Machine, and how to use that model in a Python script with TensorFlow.

**Objective**
To develop an image classification model capable of categorizing images into two distinct classes:
- Car
- Racing Bike

The goal is to leverage machine learning techniques to accurately identify and classify these categories based on visual features.

**Tools Used**
- Teachable Machine by Google
- TensorFlow 
- Keras
- Google Colab
- Python 

**How It Works**
1. The model was trained on a small dataset using Teachable Machine.
2. It was exported in TensorFlow Keras (.h5) format.
3. A custom Python script was written in Google Colab to:
   - Load the model (`keras_model.h5`)
   - Read class labels (`labels.txt`)
   - Upload a test image
   - Predict the image class and show confidence level

**Files Included**
- keras_model.h5: Trained image classification model
- labels.txt: Class names
- Image_Recognition_Task.ipynb: Python notebook for running predictions

**Model Screenshot**
![Test Model](https://github.com/amani4848/Teachable_Machine_Image_Classifier/blob/2cdb933388c37f184ef8b6423da1021c7abf86ff/Test_Model.png)


**Colab Result**
![Colab Result](https://github.com/amani4848/Teachable_Machine_Image_Classifier/blob/2cdb933388c37f184ef8b6423da1021c7abf86ff/Colab_result.png)
