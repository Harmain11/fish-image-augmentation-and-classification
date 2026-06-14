# Fish Image Augmentation and Classification

## Overview
This notebook demonstrates how to perform image augmentation on a fish image dataset using Augmentor and TensorFlow's ImageDataGenerator. It also includes training a Convolutional Neural Network (CNN) to classify fish species based on the augmented images.

## Features
- Mount Google Drive to access image datasets.
- Use Augmentor for customizable image augmentation such as rotation, flipping, and zooming.
- Apply TensorFlow's ImageDataGenerator for additional real-time data augmentation.
- Load and preprocess image datasets using `image_dataset_from_directory`.
- Build and train a CNN model to classify fish images into multiple categories.
- Visualize sample images before and after augmentation.
- Plot training and validation accuracy to monitor model performance.

## Tech Stack
- Python
- Jupyter Notebook / Google Colab
- TensorFlow (including Keras)
- Augmentor
- Matplotlib for visualization

## How to Use
1. Upload your fish image dataset to Google Drive.
2. Modify the `original_dataset_path` and `data_dir` variables to point to your dataset.
3. Run the notebook cells sequentially in Google Colab or a Jupyter environment.
4. Adjust augmentation parameters and CNN architecture as needed.
5. Review visualizations and model training results.

## Status
This notebook is organized and ready for presentation and use in GitHub repositories.