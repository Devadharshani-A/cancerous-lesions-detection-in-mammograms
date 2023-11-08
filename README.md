# cancerous-lesions-detection-in-mammograms

## Introduction
Early detection of cancerous lesions in mammograms is crucial for successful treatment and improved patient outcomes. Manually screening mammograms for abnormalities is a time-consuming and laborious task, prone to human error. This scenario aims to develop a machine learning model that can automatically detect cancerous lesions in mammograms, assisting radiologists in their diagnostic process.

## Dataset
The dataset used for this scenario is the Breast Cancer Dataset-7, obtained from Roboflow. This dataset consists of mammogram images labeled as either "normal" or "cancerous". The dataset is divided into training and validation sets for model training and evaluation.

## Data Preprocessing
No much data preprocessing is done here.
Feature Engineering
In this scenario, the mammogram images serve as the input features for the machine learning model. No additional feature engineering is required.

## Model Development
The chosen machine learning model for this task is YOLO (You Only Look Once), a state-of-the-art object detection algorithm. YOLO is well-suited for medical image analysis due to its ability to detect multiple objects in an image and its relatively fast processing speed.

## Training
The YOLO model is trained using the Breast Cancer Dataset-7. The training process involves optimizing the model's parameters to minimize the classification error between the model's predictions and the actual labels in the training data. It included Adam optimiser and 40 epochs.

## Evaluation and Accuracy
The trained YOLO model is evaluated on the validation set. The evaluation metrics include precision, recall, and F1 score. The model achieves an 0.78-0.82 mAP on the validation set, indicating its effectiveness in detecting cancerous lesions in mammograms.

## Visualization
The results of the model's detection on a sample mammogram image are displayed using a graphical visualization. 

## Conclusion
The developed model effectively detects cancerous lesions in mammograms with high accuracy. This automated detection system can potentially aid radiologists in their diagnostic workflow, improving the efficiency and accuracy of cancer detection.
