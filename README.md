# Project Overview
This project focuses on detecting football players and the football itself using the YOLOv8 model. The detection is limited to two classes: football players and the football. The project includes custom training on a dataset and visualization of the results through animations.

![fre_f_60](https://github.com/user-attachments/assets/6554f8b3-8b9e-4f9e-8db8-55e0875105a6)

# Workflow

# Install Required Libraries
Install the necessary libraries, including Ultralytics and tqdm, to support the YOLOv8 model and other utilities.

# Initialize Environment
Import essential libraries such as matplotlib, cv2, os, numpy, and PIL for image processing and animation creation.

# Prepare Dataset
Split the dataset into training and validation sets, organizing images and labels into appropriate directories.

# Train YOLOv8 Model
Train the YOLOv8 model using the custom dataset, specifying parameters like the number of epochs, image size, batch size, and project directory.

# Run Inference on Test Images
Use the trained YOLOv8 model to make predictions on a set of test images, saving the results.

# Run Inference on Video
Apply the trained YOLOv8 model to video files for object detection, adjusting confidence levels as needed.


# Dataset

The dataset utilized in this project is sourced from Kaggle's football data. It includes a diverse range of images capturing football matches with anootations in yolo format, which provide a robust foundation for training the YOLOv8 model.
# Acknowledgement 
Special Thanks to video sources:
Anastasia Shuraeva : https://www.pexels.com/video/woman-pl...
Tima Miroshnichenko : https://pexels.com/video/people-playi...
Tom Fisk: https://pexels.com/video/a-soccer-gam...
