# Brain Tumor Detection Using Deep Learning

## Overview

This project focuses on the detection of brain tumors using deep learning techniques. It involves training a convolutional neural network (CNN) model on a dataset of brain MRI images to classify them as either normal or abnormal (tumor-present). The approach includes data preprocessing, image augmentation, model training, and evaluation.

## Table of Contents

1. [What is a Brain Tumor](#what-is-a-brain-tumor)
2. [Types of Brain Tumors](#types-of-brain-tumors)
3. [Classification](#classification)
4. [Symptoms](#symptoms)
5. [Data Collection](#data-collection)
6. [Model Architecture](#model-architecture)
7. [Training the Model](#training-the-model)
8. [Evaluation Metrics](#evaluation-metrics)
9. [Conclusion](#conclusion)

## What is a Brain Tumor

A brain tumor is an abnormal growth of cells within the brain or the central nervous system.

## Types of Brain Tumors

1. **Primary Brain Tumors:** These originate in the brain or nearby structures. Examples include:
   - Gliomas
   - Meningiomas
   - Astrocytomas
   - Medulloblastomas

2. **Secondary (Metastatic) Brain Tumors:** These occur when cancer cells from other parts of the body (such as the lungs, breast, or skin) spread to the brain.

## Classification

Brain tumors can be classified as:

- **Benign (non-cancerous):** Grow slowly and generally do not spread.
- **Malignant (cancerous):** Grow aggressively and can spread to other parts of the brain or body.

## Symptoms

Symptoms of brain tumors vary depending on the tumor's size, type, and location in the brain. Common symptoms include:

- Headaches
- Seizures
- Changes in vision or hearing
- Difficulty speaking
- Memory loss
- Personality changes
- Motor skill impairments

## Data Collection

The dataset used for this project consists of MRI images of brains categorized into two classes:

- **Normal:** Images without tumors.
- **Abnormal:** Images with tumors.

### Image Augmentation

To enhance the training dataset, various image augmentation techniques are applied, including:

- Width and height shifts
- Horizontal and vertical flips

## Model Architecture

The model architecture is based on a convolutional neural network (CNN) that includes:

- **Encoder:** Several convolutional layers followed by max-pooling layers to reduce dimensionality.
- **Decoder:** Convolutional layers followed by upsampling layers to reconstruct the original image size.

## Training the Model

The model is trained using the augmented dataset, with early stopping employed to prevent overfitting. The training loss and validation loss are monitored throughout the training process.

## Evaluation Metrics

The performance of the model is evaluated using several metrics, including:

- Accuracy
- Precision
- Recall
- F1 Score

These metrics help assess the model's ability to correctly identify normal and abnormal MRI images.

## Conclusion

This project demonstrates the application of deep learning techniques in detecting brain tumors from MRI images. By leveraging CNNs and image augmentation, we can achieve effective classification, which may aid in early diagnosis and treatment of brain tumors.
