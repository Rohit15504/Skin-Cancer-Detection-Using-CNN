# Skin Cancer Detection Using CNN

## Overview
This project aims to detect melanoma, a type of skin cancer, using a Convolutional Neural Network (CNN). By leveraging deep learning techniques, the model classifies images of skin lesions as either benign or malignant.

## Dataset
The dataset used for this project is the ISIC 2019 Challenge dataset, which includes labeled images of skin lesions.

## Features
- **Data Preprocessing**: 
  - Images are resized and normalized.
  - Augmentation techniques such as rotation and flipping are applied to increase dataset diversity.
- **Model Architecture**: 
  - A CNN with multiple convolutional and pooling layers, followed by fully connected layers.
  - Utilizes dropout layers to prevent overfitting.
- **Training and Evaluation**: 
  - The model is trained using the Adam optimizer.
  - Categorical cross-entropy is used as the loss function.
  - The model’s performance is evaluated using accuracy, precision, recall, and F1-score.

## Technologies and Frameworks
- **Python**
- **TensorFlow**
- **Keras**
- **OpenCV**
- **Pandas**
- **NumPy**
- **Matplotlib**

## Results
The model achieved an accuracy of 89.61% , demonstrating its potential in aiding the early detection of melanoma.
