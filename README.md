# Smoking-Detection
This is the project to detect a person smoking by using yolov4 Object detection and Convolutional Neural Network for classification
This project is using google colab and webcam for person detection so make sure ur computer have webcam 

# Algorithm
### 1. First we use existing object detection model named yolov4
### 2. The model can detect 80 types of object but we use it specifically only to detect person
### 3. we crop the part of the image where the person is detected
### 4. we train our CNN to clasify smoking and non smoking activity
### 5. we feed the cropped image to the CNN model

# How-to Use
### 1. Open google colab and upload the ipynb file.
### 2. download the 'Smoking dataset' and upload it in your google drive (the link is in the DATASET.md file)
### 3. run the google colab file (make sure to mount colab with google drive first)
### 4. Have fun and have a play with it

# REFERENCES
This Project is highly referenced to AlexeyAB where you can find his work here https://github.com/AlexeyAB
Most of the object detection methodology is from his notebook
So, big Shout out to him
