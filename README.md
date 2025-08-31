# Flower-Classification-on-TPU-using-Deep-Learning

## Overview
This project tackles a multi-class image classification problem from a Kaggle competition, aiming to accurately recognize and differentiate between 104 flower categories. The dataset (5GB+) is provided in TFRecord format and includes diverse, imperfect real-world images, making it well-suited for robust model training. The solution leverages advanced Convolutional Neural Network (CNN) architectures such as DenseNet, ResNet, VGG19, GoogleNet, and Swin and Vision Transformers (ViT), as well as potential ensemble methods, to achieve high accuracy. To address the challenge of long training times in deep learning, the project utilizes Tensor Processing Units (TPUs) on Google Cloud through Kaggle, enabling faster convergence and reducing training time from ~8 hours to under 2 hours. The model outputs an augmented image with a bounding box around the flower, its predicted class, and confidence score, with performance evaluated using macro F1 score as the primary metric.

## Dataset 
Dataset Link: https://www.kaggle.com/competitions/tpu-getting-started/data

The dataset consists of labeled images covering 104 distinct flower categories, compiled from five publicly available datasets. It includes both images with a single flower subtype and those containing multiple subtypes. The collection captures flowers from a wide variety of angles, backgrounds, and environments, including challenging cases such as flowers appearing in unusual locations, alongside modern objects, or under varying lighting and contrast conditions. These imperfections make the dataset more robust, ensuring that models trained on it are better suited for real-world classification tasks.

The data is provided in TFRecord format, a TensorFlow-optimized container for efficient data loading and training. Each pre-split record contains an image ID, its corresponding label, and pixel array information. The complete dataset size is approximately 5.12 GB.

## Tech Stack
Programming Language: Python

Frameworks & Libraries: TensorFlow/Keras

Core Concepts: Convolutional Neural Networks (CNNs), Computer Vision

Deep Learning Architectures: DenseNet, ResNet, VGG19, GoogleNet, Vision Transformer (ViT)

Compute: Tensor Processing Unit (TPU) via Kaggle + Google Cloud Storage (GCS) integration

## Approach

## Results 
Ensemble methods yielded better classification accuracy and F1 score. Additional training data also helped in improving the F1 score. 

The best classification performance was achieved with an ensemble of EfficientNet and DenseNet with additional training data.
<img width="786" height="500" alt="image" src="https://github.com/user-attachments/assets/30c630fb-c2cb-4242-8208-bff5c1a71c50" />

## Contributing
Contributions are welcome! Please fork the repo and submit a pull request.
