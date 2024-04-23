# Scene Image Classification Using CNN and Ensemble Learning

## Project Overview
This project focuses on developing a robust image classification system using Convolutional Neural Networks (CNN) enhanced by ensemble learning techniques. The goal is to accurately classify images into predefined scene categories, which can be utilized in various applications such as digital media management and automated monitoring systems.

## Installation

### Prerequisites
- Python 3.8 or above
- pip3

### Dependencies
Install the required packages using the following command:
```bash
pip install -r requirements.txt

Dataset

The dataset used in this project consists of 1,500 images distributed across 15 different categories. Each category contains 100 images. Due to privacy or size constraints, the dataset is not included in the repository. Instructions for accessing and downloading the dataset are provided below.
Downloading the Dataset

    Access the dataset at: [Google Drive]
    Download and extract the dataset into the data/ directory within the project folder.

Usage
Training the Model

To train the model, navigate to the project directory and run:

bash

python train.py

This script will train the CNN model using the data located in data/train. The trained model will be saved in the models/ directory.
Evaluating the Model

To evaluate the model's performance on the validation set, run:

bash

python evaluate.py

This will load the trained models from the models/ directory and perform evaluation on the data in data/validation.
Using the Ensemble Model

To use the ensemble model for prediction, run:

bash

python predict.py --image_path 'path_to_image'

Replace path_to_image with the actual path to the image you want to classify.
Contributing

    Ji Chunlei: Led the coding, model training, and documentation.
    Lin: Assisted in code refinement and provided significant inputs on model parameter tuning and report editing.
