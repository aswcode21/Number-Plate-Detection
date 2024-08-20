# Licence-Plate-Detection-using-YOLO-V8

 # Project Overview
This project focuses on detecting non-standard number plates and classifying them into two categories: standard and non-standard. The detection and classification process is powered by a YOLOv8 model, which has been trained to recognize and predict number plates from images. For number plate recognition, EasyOCR has been utilized to extract text from detected plates.

# Data Annotation and Splitting
Annotations: The dataset was annotated using CVAT.ai, which allowed for precise labeling of number plates.
Dataset Splitting: The dataset has been split into training, testing, and validation sets using Roboflow, ensuring a well-balanced distribution for model evaluation and training.

# Model Training and Detection
Model: YOLOv8 is used for training the model to detect and classify number plates. YOLOv8 provides high accuracy and efficiency for real-time object detection tasks.
Prediction: The trained YOLOv8 model is used for making predictions on new images to classify number plates as either standard (0) or non-standard (1).

# Number Plate Recognition
Tool: EasyOCR is employed to perform Optical Character Recognition (OCR) on the detected number plates to extract and recognize the text content.

# Dataset Access
If you are interested in viewing or using the dataset, it is available on my Roboflow account. The dataset includes annotated images for training and evaluation of the model.
