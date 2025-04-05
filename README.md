# CLASP – CLassification of Abnormal Seizure Patterns (Biomedical Signal Processing)

## Introduction

 The challenge is to build a machine learning model that can classify different types of seizures from **EEG signals**. The aim is to create a model that not only identifies seizure types but also provides **explainable insights** to help clinicians understand and trust the model's decisions.

### Dataset Overview:
The dataset consists of EEG signals categorized into four classes:
1. **Normal**
2. **Complex Partial Seizures**
3. **Electrographic Seizures**
4. **Video Detected Seizures with No Visual Change Over EEG**

### Objectives:
The challenge is to preprocess, analyze, and build a robust machine learning model for classifying these EEG signals. A key focus is on **model explainability** to assist healthcare professionals in interpreting the results.

### Repository Highlights:
This repository covers several aspects of the project:

#### 1. **Preprocessing and Feature Extraction**
   - **Goal**: Analyze EEG signals using time-domain and frequency-domain techniques.
   - **Methods**: Extract meaningful features, including statistical metrics and Fourier Transforms.

#### 2. **Model Building**
   - **Goal**: Develop a baseline machine learning model and improve it.
   - **Methods**: Experiment with different techniques and models for better classification accuracy.

#### 3. **Explainability**
   - **Goal**: Ensure transparency and trust in the model’s decisions.
   - **Methods**: Use tools like **SHAP** to understand model predictions and make the process interpretable for clinicians.

#### 4. **Denoising**
   - **Goal**: Handle noisy EEG data.
   - **Methods**: Apply signal denoising methods to improve model performance.

#### 5. **Generative Modeling**
   - **Goal**: Augment the training set with synthetic EEG data.
   - **Methods**: Use generative algorithms to enhance model training and boost performance.

### Our Aim:
The ultimate goal is not only to achieve high classification accuracy but also to create a model that is **interpretable**, **efficient**, and **practical for real-world healthcare applications**.

### Repository Structure:
The repository is designed to ensure **reproducibility** and **clarity**. It includes detailed explanations, code, insights, and visualizations to make the process transparent and easy to follow.

In the following sections, you'll find a breakdown of the approach taken for each task, along with the code, insights, and results that contributed to the best possible outcome for this challenge.
