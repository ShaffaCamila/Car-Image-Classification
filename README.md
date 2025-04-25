# 🚗 CNN Car Classification

This project is a Convolutional Neural Network (CNN) model designed to classify images of cars into seven distinct classes. The model leverages deep learning techniques to accurately identify and categorize car images.

## 🏎️ Classes
The model is trained to classify the following car types:
- **🚘 Audi**
- **🚙 Hyundai Creta**
- **🚗 Mahindra Scorpio**
- **🚔 Rolls Royce**
- **🚖 Swift**
- **🚜 Tata Safari**
- **🚐 Toyota Innova**

## ✨ Features
- Utilizes a CNN architecture for image classification.
- Preprocessed dataset with labeled car images for training and testing.
- High accuracy in distinguishing between the seven car classes.

## 📋 Requirements
- Python 3.x
- TensorFlow/Keras
- NumPy
- Matplotlib
- Further information check requirement.txt

## 📂 Dataset

Ensure the dataset is organized into folders corresponding to the seven classes.  
Each folder should contain images of the respective car type.

You can download the dataset used for this project from the following link:  
🔗 [Cars Image Dataset on Kaggle](https://www.kaggle.com/datasets/kshitij192/cars-image-dataset)

## 📊 Results
The trained model achieves high accuracy in classifying car images into the specified classes. Below are the performance metrics:

### Training Results
- **Accuracy**         : 91.19%
- **Loss**             : 0.0980

### Testing Results
- 📉 **Test Loss**     : 0.0989
- ✅ **Test Accuracy** : 90.48%

### Dataset Details:
- 🔹 **Total data train**      : 5670  
- 🔹 **Total data validation** : 707  
- 🔹 **Total data test**       : 714  
- 📊 **Jumlah kelas**          : 7  
- 🏷️ **Label mapping**         :  
    `{'Audi': 0, 'Hyundai Creta': 1, 'Mahindra Scorpio': 2, 'Rolls Royce': 3, 'Swift': 4, 'Tata Safari': 5, 'Toyota Innova': 6}`