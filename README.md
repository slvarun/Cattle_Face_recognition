
# Siamese Network for cattle identification

## Description
This project implements a Siamese neural network for image similarity comparison of various cattle mainly focussing on cows using TensorFlow and Keras.
It take the muscle features of a cow as reference to check the similarity score.

## Installation
To run this code, make sure you have Python installed. Install the required dependencies using pip:

```bash
pip install -r requirements.txt
```
To use this code, follow these steps:


## Useage
1) Clone the repository :
  ```bash
  git clone https://github.com/your_username/cow-muzzle-siamese.git
```
3) Install dependencies :
```bash
  pip install -r requirements.txt
```
5) Run the main script :
```bash
  python app.py
```
## Model Architecture
The Siamese neural network architecture consists of convolutional layers followed by fully connected layers. The model takes pairs of muzzle images, processes them through the encoder, calculates the cosine similarity between their embeddings, and outputs a binary classification result.

## Graphs

### Training and Validation Loss

![Training and Validation Loss](images/Loss.png)

This graph shows the training and validation loss over epochs during the training process. Lower loss values indicate better performance of the model.

### Training and Validation Accuracy

![Training and Validation Accuracy](images/accuracy.png)

This graph illustrates the training and validation accuracy over epochs. Higher accuracy values indicate better performance of the model in classifying muzzle images.

### ROC Curve

![ROC Curve](images/roc_curve.png)

The Receiver Operating Characteristic (ROC) curve plots the true positive rate against the false positive rate for various threshold settings. It helps visualize the performance of the model in binary classification tasks.

## Training Details

- **Number of Epochs**: 15
- **Batch Size**: 64

The model was trained for 15 epochs with a batch size of 64. Adjustments to hyperparameters such as epochs and batch size can impact the model's performance and training time.


=======
# Cow Identification and Registration Web Application

## Overview

This Flask web application uses a Siamese neural network model for cow identification and registration. Users can add cow details, including owner information and an image of the cow. The application also allows users to identify a cow by uploading an image, and it checks for similarity with previously registered cows.

## Features

- User-friendly web interface for cow registration and identification.
- Siamese neural network for calculating similarity between cow images.
- MongoDB database for storing cow registration details.

## Prerequisites

Make sure you have the following installed on your machine:

- Python (3.6 or higher)
- Flask
- NumPy
- TensorFlow
- Keras
- Pillow (PIL)
- PyMongo (for MongoDB integration)

Install the required Python packages using the following command:

## *Project Contributors:*
- Hima Vamshi
- A. Sai Tharun
- G. Rohith Reddy
- M.Varun
- Bhanu Teja
- Vasu Dev

