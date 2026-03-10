# Image Inpainting with CNN Models

## Overview
This repository contains the official implementation of my final project for **ECE 176 (Deep Learning & Applications)** at UC San Diego. 
The goal of this project is to restore missing or corrupted regions of images using Convolutional Neural Networks (CNNs).

## Model Architecture & Tech Stack
* **Framework:** PyTorch
* **Core Architecture:** Convolutional Neural Network (CNN) 
* **Loss Function:** Average / 0.0074791633524000645
* **Optimization:** Back-propagation implemented for model training.

## Results
Here is a visual comparison of the model's performance on the dataset. The model takes the corrupted image as input and reconstructs the missing pixels to match the ground truth.

Original Image (Ground Truth)
<img width="794" height="180" alt="1" src="https://github.com/user-attachments/assets/870bd2fa-5638-4bcc-8673-fc8290cca683" />

Restored Image (Output)
<img width="794" height="180" alt="3" src="https://github.com/user-attachments/assets/d3b439ba-8d11-44b0-b121-87e65f165590" />

*(Note: Please refer to the Jupyter Notebooks for the complete training pipeline and data preprocessing steps.)*
