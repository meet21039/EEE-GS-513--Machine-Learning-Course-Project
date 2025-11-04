# EEE-GS-513--Machine-Learning-Course-Project

# 🧠 Brain MRI Tumor Classification

This project focuses on classifying **Brain MRI images** into four categories using **Convolutional Neural Networks (CNNs)**:

- Glioma  
- Meningioma  
- Pituitary  
- No Tumor  

The model is trained and evaluated on a curated MRI dataset, with separate training and testing folders for each class.  
This work was done as part of the **EEE-GS-513 Machine Learning Course Project**.

---


## 🚀 Project Overview

### 🎯 Objective
To automatically classify MRI brain scans into four categories using deep learning techniques, improving accuracy and efficiency in tumor detection.

### 💡 Methodology
1. **Dataset Preparation**
   - Organized MRI scans into folders: `glioma/`, `meningioma/`, `pituitary/`, `no_tumor/`.
   - Split into training and testing sets.
   - Applied normalization and data augmentation (rotation, flip, zoom).

2. **Model Architecture**
   - Baseline CNN with multiple convolutional + pooling layers.
   - Metrics: Accuracy, AUC (Area Under Curve).

3. **Training & Evaluation**
   - Trained on Google Colab using GPU runtime.
   - Early stopping and checkpointing used for best model retention.
   - Evaluated using confusion matrix, ROC AUC, and classification report.

# 🩻 X-Ray Image Classification using CNN

This project focuses on classifying **medical X-ray images** into categories (such as *Normal*, *Pneumonia*, or *Fracture*) using **Convolutional Neural Networks (CNNs)**.

The model automates disease detection from X-rays to assist radiologists in preliminary screening and faster diagnosis.

This work was developed as part of the **EEE-GS-513 Machine Learning Course Project**.

---

---

## 🚀 Project Overview

### 🎯 Objective
To classify X-ray images into medical categories using deep learning techniques for assisting medical professionals in diagnosis.

### 💡 Methodology
1. **Dataset Preparation**
   - X-ray images organized into folders (e.g. `Normal/`, `Fracture/`).
   - Split into training and testing sets.
   - Preprocessing steps include resizing, normalization, and data augmentation (rotation, zoom, flip).

2. **Model Architecture**
   - A custom **CNN** built from scratch using TensorFlow/Keras.
   - Multiple convolution and pooling layers followed by dense layers.

3. **Training & Evaluation**
   - Training done on Google Colab GPU.
   - Used **EarlyStopping** and **ModelCheckpoint** for efficient training.
   - Evaluation includes accuracy, confusion matrix, and ROC AUC metrics.





