# Deep-Learning-Project-CIFAR-100-Subset-Classification-and-Selfie-Emotion-Detection


## Overview
This project focuses on developing and evaluating deep learning models for two classification tasks. The first task involves classifying a subset of the CIFAR-100 dataset (animals and people categories) using two transfer learning-based models: MobileNet and EfficientNetV2. The second task performs binary classification (happy vs. sad) on a custom dataset of selfie images.

## Project Structure
- **Deep_learning_project.ipynb**: The main Jupyter Notebook containing the code for both tasks, including data preprocessing, model training, evaluation, and analysis.
- **Dataset**:
  - **CIFAR-100 Subset**: A subset of the CIFAR-100 dataset, filtered to include only animals and people classes (50 categories).
  - **Selfie Dataset**: 24 images (12 happy, 12 sad) for binary emotion classification (not included in the repository; users must provide their own dataset).
- **Requirements**: Python libraries used include TensorFlow, Keras, NumPy, Matplotlib, and others (see below for installation).

## Tasks
### Task 1: CIFAR-100 Subset Classification
- **Objective**: Design, implement, and evaluate two deep learning models (MobileNet and EfficientNetV2) using transfer learning for classifying a subset of CIFAR-100 images (animals and people, 50 classes).
- **Steps**:
  1. Load and preprocess the CIFAR-100 dataset, filtering for animals and people classes.
  2. Implement MobileNet and EfficientNetV2 models with transfer learning.
  3. Train and evaluate both models on the dataset.
  4. Compare model performance (accuracy, loss, etc.) to select the better-performing model.
- **Output**: Performance metrics (accuracy, loss) and visualizations for both models.

### Task 2: Selfie Emotion Classification
- **Objective**: Use the better-performing model from Task 1 to perform binary classification (happy vs. sad) on a custom selfie dataset.
- **Steps**:
  1. Prepare a dataset of 24 selfie images (12 happy, 12 sad).
  2. Fine-tune the selected model for binary classification.
  3. Train and evaluate the model on the selfie dataset.
- **Output**: Binary classification results and performance metrics.


## Results
- **Task 1**: The notebook includes performance comparisons (accuracy, loss, etc.) for MobileNet and EfficientNetV2 on the CIFAR-100 subset. Visualizations (e.g., training curves, confusion matrices) are provided.
- **Task 2**: Binary classification results for the selfie dataset, including accuracy and loss metrics.
