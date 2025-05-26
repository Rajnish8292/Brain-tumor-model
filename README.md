#  Brain Tumor Classifier

A deep learning project that classifies brain MRI images into four categories: **glioma tumor**, **meningioma tumor**, **pituitary tumor**, and **no tumor**. This model assists in preliminary tumor detection and classification using medical imaging.

##  Project Overview

The model was trained on a labeled dataset of brain MRI scans using a Convolutional Neural Network (CNN). It achieved a **validation accuracy of 72.06%** and helps in identifying the presence and type of tumor with reasonable accuracy.

##  Classes 

-  **Glioma Tumor**
-  **Meningioma Tumor**
-  **Pituitary Tumor**
-  **No Tumor**

## 🛠 Technologies Used

- Python
- TensorFlow / Keras
- OpenCV
- NumPy, Pandas
- Matplotlib, Seaborn (for visualization)
- Scikit-learn (for metrics and evaluation)

##  Dataset

The dataset was sourced from [Kaggle - Brain Tumor Classification (MRI)](https://www.kaggle.com/code/shiratorizawa/brain-tumor-detection-using-cnn) and contains labeled MRI scans divided into 4 categories.

##  Model Architecture

- Input Layer: 150x150 pixel grayscale images
- 5 Convolutional Layers (with ReLU + MaxPooling + Batch Normalization + Kernel Reguarizer + Dropouts)
- Flatten Layer
- Dense Layers with Dropout
- Output Layer: Softmax activation (4 classes)

## 📊 Performance

- **Validation Accuracy:** 72.06%

## Author
Made by Rajnish Raj
### Connect on [LinkedIn](https://www.linkedin.com/in/rajnish-raj-9139602a4/)



