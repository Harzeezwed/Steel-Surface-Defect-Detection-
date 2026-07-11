# Steel Surface Defect Detection with Foundation Models

## Overview

This project investigates the use of modern computer vision and foundation models for automated steel surface defect detection using the NEU Surface Defect Database.

The study compares multiple learning paradigms, including zero-shot learning, few-shot learning, and supervised fine-tuning, while incorporating explainable AI techniques to understand model decisions.

## Dataset

### NEU Surface Defect Database

The dataset contains 1,800 grayscale steel surface images across six defect categories:

* Crazing
* Inclusion
* Patches
* Pitted Surface
* Rolled-in Scale
* Scratches

Each class contains 300 annotated images.

## Project Objectives

* Perform exploratory data analysis on steel defect images.
* Develop classification and detection pipelines.
* Evaluate foundation models under limited-data conditions.
* Compare zero-shot, few-shot, and fine-tuned approaches.
* Interpret model predictions using Grad-CAM visualizations.

## Methodology

### Data Preparation

* Image preprocessing
* Annotation parsing
* Train/Validation/Test split
* Data augmentation

### Learning Approaches

#### Zero-Shot Learning

Leverage pretrained vision-language models without task-specific training.

#### Few-Shot Learning

Adapt foundation models using limited labeled examples.

#### Fine-Tuning

Train pretrained models on the NEU defect dataset for improved performance.

### Explainability

* Grad-CAM
* Attention visualization
* Feature interpretation

## Technologies

* Python
* PyTorch
* Torchvision
* Hugging Face Transformers
* OpenCV
* Scikit-Learn
* Matplotlib
* Grad-CAM

## Results

The project evaluates:

* Classification Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix
* Explainability Visualizations

## Applications

* Smart Manufacturing
* Quality Control
* Industrial Inspection
* Defect Monitoring
* Predictive Maintenance

## Author

Abiola Azeez Muhyideen

PhD Student, Industrial Engineering

Arizona State University



