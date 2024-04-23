# Machine Learning Project: ECS7020P Mini-Project

## Overview

This Machine Learning project utilizes the MLEnd Yummy Dataset and is divided into two main components, each addressing a distinct classification challenge with separate Jupyter notebooks:

1. **Basic Component:** Develops a machine learning pipeline for classifying images of dishes as containing either rice or chips.
2. **Advanced Component:** Explores a unique machine learning challenge using the dataset, focusing on distinguishing between Chicken and Potato dishes.

## Project Structure

The project comprises the following Jupyter notebooks:
- `ECS7020P_miniproject_basic.ipynb`: Implements the basic component.
- `ECS7020P_miniproject_advanced.ipynb`: Covers the advanced component.

## Details of Machine Learning Models and Results

### Basic Component: RandomForestClassifier
- **Training Accuracy:** 89.42%
- **Testing Accuracy:** 66.07%
- **Misclassification Rates:**
  - Rice misclassified as Chips: 32%
  - Chips misclassified as Rice: 36%
  - Chips correctly identified: 64%
- **Insights:** The model shows good training performance but indicates potential overfitting, as evidenced by the drop in testing accuracy.

### Advanced Component: Linear Support Vector Classifier (LinearSVC)
- **Training Accuracy:** 60.58%
- **Testing Accuracy:** 56.97%
- **Performance Details:**
  - Chicken correctly identified: 68%
  - Potato correctly identified: 47%
- **Insights:** The model demonstrates moderate accuracy with more effective recognition of Chicken dishes over Potato dishes. Potential issues include overfitting and a challenge in differentiating Potato images.
