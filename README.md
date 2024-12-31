# Diabetic-Retinopathy-Detection
Diabetic Retinopathy Detection using Transfer Learning and Explainable AI

## Overview

This project aims to classify diabetic retinopathy levels from retinal fundus images using state-of-the-art deep learning techniques. The project involves transfer learning with pretrained models, advanced preprocessing methods, attention mechanisms, and ensemble learning. Additionally, Grad-CAM visualizations are employed to explain the decision-making process of the models.

## Key Features

1. **Transfer Learning:** Fine-tuning of pretrained models like ResNet18, DenseNet, and VGG16.
2. **Two-stage Training:** Transfer learning on an auxiliary dataset (APTOS 2019) followed by fine-tuning on the DeepDRiD dataset.
3. **Attention Mechanisms:** Integration of Squeeze-and-Excitation (SE) blocks to improve feature weighting.
4. **Image Preprocessing:** Application of various preprocessing techniques such as Ben Graham's resizing, CLAHE, Gaussian blur, sharpening, and circular cropping.
5. **Ensemble Learning:** Implementation of stacking, boosting, bagging, max voting, and weighted averaging for enhanced performance.
6. **Explainable AI:** Grad-CAM visualizations to identify the regions of fundus images that influence model predictions.

## Dataset

The primary dataset used for this project is **DeepDRiD**. Additionally, the **APTOS 2019** dataset was utilized for the two-stage training approach. Both datasets consist of labeled retinal fundus images with diabetic retinopathy levels.

- DeepDRiD Dataset: [Link to DeepDRiD Challenge](https://www.sciencedirect.com/science/article/pii/S2666389922001040)
- APTOS 2019 Dataset: [Kaggle APTOS Challenge](https://www.kaggle.com/c/aptos2019-blindness-detection/overview)

## Repository Contents

- **`deeplearning_course_project.ipynb`:** The main notebook containing code for data preprocessing, model training, evaluation, and visualization.
- **`README.md`:** Overview and details about the project.
