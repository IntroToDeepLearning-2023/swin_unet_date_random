# Crop Type Segmentation with Swin Transformer

## Overview

This repository contains code for a Crop Type Segmentation model based on the Swin Transformer architecture. The model is trained to segment different crop types from satellite imagery.

## 1. Data Source

The dataset used for training and validation is sourced from Google Cloud Platform (GCP). The dataset includes satellite images from various sources, including PlanetScope and Sentinel-2.

### .2. Accessing Data on GCP

To access the dataset on GCP, follow these steps:

1. **GCP Account Setup:**
   - Ensure you have access to the Google Cloud Platform with the necessary permissions.

2. **Dataset Location:**
   - The dataset is stored in a GCP Storage Bucket. You can find the dataset at the following location: `gs://your-bucket/dataset-folder`.

3. **Data Loading:**
   - The training and validation scripts in this repository are configured to load data directly from the GCP Storage Bucket. Ensure that your GCP credentials are set up correctly on the machine running the code.

## 3. Model Architecture

The segmentation model is based on the Swin Transformer architecture, a recent advancement in computer vision. The model is designed for effective segmentation of crop types from satellite imagery.

## 4. Training

The training script (`train.py`) includes the complete pipeline for training the model. Make sure to set up the necessary dependencies and configurations before running the script.

### 5. Configuration

Adjust the training configurations in the `config` dictionary in the script. Key configurations include the number of epochs, learning rate, loss weights, etc.

### 6. Running the Training Script

```bash
python train.py
```
## 7. Evaluation

The evaluation script (`evaluate.py`) is designed to assess the performance of the trained model on a separate validation dataset.

Running the Evaluation Script
`python evaluate.py`

## 8. Results

The trained model achieves competitive results in terms of accuracy, F1 score, and other relevant metrics. Check the WandB dashboard for detailed logs and visualizations.

Important Note:

This is a general overview of the visualization process.

## Contributors

- **Deo Uwimpuhwe**
  - Program: MECE 2024
  - Email: [duwimpuh@andrew.cmu.edu](mailto:duwimpuh@andrew.cmu.edu)

- **Gustave Bwirayesu**
  - Program: MECE 2024
  - Email: [gbwiraye@andrew.cmu.edu](mailto:gbwiraye@andrew.cmu.edu)

- **Eric Maniraguha**
  - Program: MSIT 2024
  - Email: [emanirag@andrew.cmu.edu](mailto:emanirag@andrew.cmu.edu)

- **Bienvenue Jules Himbaza**
  - Program: MECE 2024
  - Email: [hjulesbi@andrew.cmu.edu](mailto:hjulesbi@andrew.cmu.edu)

# Fun Fact! 🚀

Did you know? AI stands for "Amusing Intelligence"! Because making computers smart can be a whole lot of fun! 😄
