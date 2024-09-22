# Image Colorization using Conditional Wasserstein GAN


## Overview

This repository focuses on image colorization using a Conditional Wasserstein Generative Adversarial Network (CWGAN). The CWGAN is designed to colorize grayscale images, leveraging a combination of generator and critic networks based on Residual Blocks. The training process involves optimizing the generator to produce realistic colorizations while concurrently training the critic to discern between real and generated colorizations.

## Prerequisites

Before diving into the code, make sure you have the following dependencies installed:

- PyTorch
- PyTorch Lightning
- NumPy
- Matplotlib
- OpenCV
- Scikit-Image


## Data Preparation

Begin by downloading the required datasets using the provided Kaggle data sources. Execute the cell at the beginning of the notebook to import the datasets into the correct location.

## Usage

The primary notebook (`image_colorization_cwgan.ipynb`) provides step-by-step guidance through the entire process, covering data loading, model training, and evaluation. Follow the notebook instructions to train the CWGAN model and generate captivating colorized images.

## Model Architecture

The CWGAN architecture encompasses a generator and a critic, with the generator featuring encoding and decoding layers incorporating residual blocks. Simultaneously, the critic employs convolutional layers. Both networks are adept at handling grayscale-to-color image translation.

## Results

Witness the model's performance through the visualization of generated colorized images during training. Additionally, leverage Inception Score and Fréchet Inception Distance (FID) for a quantitative evaluation. Pretrained models are saved at various epochs for future use.

## Evaluation

Evaluate the quality and diversity of the generated colorizations using Inception Score and FID. These metrics provide valuable insights into the realism and variety of the colorized images compared to real images.

Feel free to experiment with hyperparameters, architecture, and training duration to achieve superior results. You can also adapt the code to suit your specific use case.


