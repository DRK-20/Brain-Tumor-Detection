# Brain Tumor Detection

![image](https://github.com/DRK-20/Brain-Tumor-Detection/assets/97865229/a2ee439b-22ca-4916-bdde-2803799ee6e5)

## Overview
This repository contains a brain tumor detection system implemented using Convolutional Neural Networks (CNNs). The system is designed to accurately identify and classify brain tumors in medical images, specifically MRI scans. By leveraging deep learning techniques, the project aims to assist medical professionals in the early diagnosis and treatment planning of brain tumors.

## Dataset
The brain tumor detection system was trained and evaluated on the Brain Tumor MRI Dataset available on Kaggle. The dataset consists of annotated MRI scans of patients with and without brain tumors, providing a valuable resource for training and testing the model.
Dataset Link - https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset?select=Testing

## Model Architecture
The brain tumor detection system utilizes a Convolutional Neural Network (CNN) model. CNNs are well-suited for image classification tasks as they can effectively learn hierarchical features and patterns from the input data. The architecture of the CNN model used in this project comprises several convolutional layers, followed by pooling and fully connected layers, enabling the model to learn discriminative features for accurate tumor detection.

![model](https://github.com/DRK-20/Brain-Tumor-Detection/assets/97865229/bd020c2f-4ddb-44e4-965d-2ede0a0f4b5b)

## Model Performance
The trained CNN model achieved impressive performance on the brain tumor detection task. The model was evaluated on a separate testing set, resulting in a testing accuracy of 99.07%. During training, the model was validated on a validation set, achieving a validation accuracy of 93.67%. These high accuracy scores indicate the model's ability to accurately classify brain tumors in MRI scans.

## Installation
To set up the brain tumor detection system locally, follow these steps:

1. Clone this repository to your local machine.
   
   git clone https://github.com/your-username/brain-tumor-detection.git
   
2. Install the required dependencies by running the following command.
   
   pip install -r requirements.txt
