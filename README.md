# PetalTorch : 🌸 Flower Classifier with PyTorch

📖 Project Overview

-Uses transfer learning with pre-trained models (vgg19 or densenet121).
-Converts the model into a command-line application for training and inference.
-Predicts the name of the flower and provides the confidence level (probability) for the prediction.

📂 Repository Contents

PetalTorch/

├── train.py             # Script for training the model

├── predict.py           # Script for testing the model

├── cat_to_name.json     # JSON file mapping category labels to flower names

├── checkpoint.pth       # Saved model checkpoint

├── README.md            # Documentation

└── data/                # Dataset folder

🛠️ Tools & Technologies Used
Python 3.7+: Core programming language.
PyTorch: Framework for deep learning and transfer learning.
Torchvision: Used for pre-trained models and data transformations.
Matplotlib: For visualization of results and metrics.
Amazon Web Services (AWS): Supports GPU-enabled training.
Command-Line Interface (CLI): For running the training and prediction scripts.

🚀 Features

#Transfer Learning:
-Pre-trained models (vgg19, densenet121) for efficient training.

#Command-Line Interface:
-Train and test the model via CLI.

#Customizable Training:
-Choose GPU or CPU for training.
-Specify the number of training epochs and learning rate.

#Flower Name Prediction:
-Predict the flower name from an image.
-Show confidence levels for predictions.

📈 Results
Best Model: DenseNet121 achieved 97.5% accuracy on the test set.
