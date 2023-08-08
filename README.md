# BPCL
This project is based on the image classification of cylinders.
I have to classify the images of cylinder based on the presence of Oring inside the Gas cylinder valves.
This project is divided into two parts now 
  1. Object detection
  2. Image classification

1. Object detection:- Here I have to detect the cylinder's valve by using a custom object detection model which returns the coordinates of the object from an image which
                      then can be used for cropping the images which removes the unwanted information while classification.
2. Image classification:- After getting a cropped image from the object detection algorithm image will be sent for classification.
