# Chest X-ray Disease Classification
This project focuses on classifying chest X-ray images into normal and abnormal categories. It uses a Convolutional Neural Network (CNN) model to analyze X-ray images along with clinical data, aiming to assist in the early detection of lung diseases.

## Table of Contents

- [Dataset](#dataset)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Results](#results)
- [Dependencies](#dependencies)
- [Contributing](#contributing)

## Dataset

The dataset consists of chest X-ray images and clinical readings. It's structured into two main categories:

- **Normal:** Chest X-ray images without apparent abnormalities.
- **Abnormal:** Chest X-ray images indicating the presence of lung diseases.

The dataset can be found in the `/kaggle/input/chest-xray-masks-and-labels/` directory, including the clinical readings and mask images.

## Getting Started

To get started with this project, follow these steps:

1. Clone this repository to your local machine:

   ```bash
   git clone <https://github.com/Venkat-Kancherla-1/lung_disease_detection.git>

## Usage

lung-disease-detection.ipynb contains the code for data preprocessing, model creation, training, and evaluation.
The model is trained on chest X-ray images and clinical data to classify them as normal or abnormal.
Use the provided ModelCheckpoint callback to save the best model weights during training.

## Results 
The classification model achieved an accuracy of 76% on the test dataset. While this is a promising start, further optimization and fine-tuning can improve model performance.

## Dependencies
Python (>=3.6)
TensorFlow (>=2.0)
Numpy
OpenCV
Matplotlib
scikit-learn

## Contributing
Contributions are welcome! If you'd like to contribute to this project, please follow these guidelines:

Fork the repository.
Create a new branch for your feature or bug fix.
Make your changes and commit them with clear, concise commit messages.
Push your branch to your fork.
Open a pull request to the master branch of this repository.

Here, I attached the kaggle link of my work https://www.kaggle.com/code/kancherlavenkat/lung-disease-detection