# Breast-Histopathology-Image-Classification


This project is part of the **KV7006 Machine Learning module** at Northumbria University. It focuses on classifying breast histopathology images to detect **Invasive Ductal Carcinoma (IDC)** using deep learning models.

## Files

- `Assignment2_KV7006.ipynb` – Jupyter notebook implementing a CNN and a pretrained EfficientNetB0 model.
- Dataset used: **Breast Histopathology Images (IDC)**.

## Models Implemented

- ✅ **Model 1** – Custom Convolutional Neural Network (CNN)
- ✅ **Model 2** – **EfficientNetB0 (Transfer Learning)** – pretrained on ImageNet

## Performance Evaluation

Both models were evaluated using:
- Accuracy
- Precision, Recall, F1-Score
- Confusion Matrix
- ROC-AUC

## Technologies Used

- Python
- TensorFlow / Keras
- NumPy, Pandas
- Matplotlib, Seaborn
- scikit-learn

## Project Highlights

- Focused on binary classification (IDC vs Non-IDC).
- Applied data preprocessing, augmentation, and resizing for deep learning compatibility.
- Used **EfficientNetB0** with transfer learning, significantly outperforming the baseline CNN.

## Author

**Smriti**  
MSc Data Science, Northumbria University  
Student ID: 24041442  
Module: KV7006 – Machine Learning
