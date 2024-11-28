# Lung Cancer Classification Using CoAtNet

This repository contains the implementation of a machine learning project aimed at classifying histopathological lung images into three categories: adenocarcinoma, squamous cell carcinoma, and benign. The project leverages the CoAtNet architecture, which combines convolutional layers and self-attention mechanisms to achieve high classification accuracy.

This project was developed as a final assignment for [Asem](https://www.asemedu.com/) workshop on CNN 

---

## Table of Contents
1. [Introduction](#introduction)
2. [Dataset](#dataset)
3. [Results](#results)
4. [Challenges Faced](#challenges-faced)
   
---

## Introduction
Lung cancer is a leading cause of cancer-related deaths worldwide, and early detection is critical for improving patient outcomes. This project uses a deep learning approach to classify lung cancer histopathological images, providing an automated tool to assist medical professionals in diagnosis. The CoAtNet model, a hybrid of convolutional networks and transformers, was selected for its ability to handle both local and global feature extraction efficiently.

---

## Dataset
The [dataset](https://www.kaggle.com/datasets/rm1000/lung-cancer-histopathological-images) used consists of histopathological images of lung tissue, categorized as:
- **Adenocarcinoma**
- **Squamous Cell Carcinoma**
- **Benign**

Since expertise in lung cancer diagnosis is required to label the images accurately, pre-labeled datasets were used. The dataset underwent preprocessing steps such as resizing, normalization, and data augmentation.

---


## Results
![confusion matrix]()

![pic](https://github.com/user-attachments/assets/482b9065-cbe8-4ea1-ab8d-e3d2dc162346)

---

---


## Challenges Faced

- **Dataset Labeling:** Lack of medical expertise made it difficult to validate image labels manually.
- **Self-Attention Mechanism:** Implementing self-attention required extensive research, as it was not covered in prior coursework.
- **Training:** The model required large amount computational resources and time for training. 1 night for implementation and training is not enough 😢 


---

