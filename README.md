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

## 📂 Project Structure

BrainMRI-Classification/
│
├── data_pipeline/
│ └── preprocess.py # dataset loading & preprocessing functions
│
├── models/
│ └── final_mri_model.keras # trained model saved in Keras 3 format
│
├── notebooks/
│ └── BrainMRI_Classification.ipynb # main Colab notebook
│
├── results/
│ ├── accuracy_loss_plot.png
│ ├── confusion_matrix.png
│ └── classification_report.txt
│
├── requirements.txt # dependencies
└── README.md # project overview
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
   - Trained using **Adam optimizer** and **categorical cross-entropy loss**.
   - Metrics: Accuracy, AUC (Area Under Curve).

3. **Training & Evaluation**
   - Trained on Google Colab using GPU runtime.
   - Early stopping and checkpointing used for best model retention.
   - Evaluated using confusion matrix, ROC AUC, and classification report.

---

## 📊 Results

| Metric | Value |
|---------|-------|
| Accuracy | 0.93 |
| ROC AUC  | 0.96 |
| Loss     | 0.21 |

### Confusion Matrix
![Confusion Matrix](results/confusion_matrix.png)

---

## 🧩 How to Run

### 🖥️ In Google Colab
1. Clone this repository:
   ```bash
   !git clone https://github.com/meet21039/EEE-GS-513-Machine--Learning-Course-Project.git
   %cd EEE-GS-513-Machine--Learning-Course-Project

