# CIFAR-10 Convolutional Neural Network (CNN) 👁️🧠

An extended deep learning project implementing a Convolutional Neural Network (CNN) to classify the **CIFAR-10** image dataset. 

While a standard Multi-Layer Perceptron (MLP) flattens images and loses spatial hierarchies, this CNN architecture leverages convolutional filters and pooling layers to extract spatial features (edges, textures, and shapes), significantly improving classification accuracy and model robustness.

## 🎯 Project Overview
The CIFAR-10 dataset consists of 60,000 32x32 color images across 10 distinct classes. This project builds a deep CNN from scratch, exploring how spatial convolutions overcome the limitations of dense networks in computer vision tasks.

## 🚀 Key Features
* **Spatial Feature Extraction:** Implementation of 2D Convolutional layers (`Conv2d`) and Max Pooling layers to capture spatial hierarchies.
* **Extended Architecture:** Features an advanced network topology compared to baseline models, potentially including deeper layers, Batch Normalization, or Dropout for regularization.
* **Data Processing:** Tensor transformations, normalization, and (if applicable) data augmentation pipelines to prevent overfitting.
* **Performance Tracking:** Visual tracking of the training loss and validation accuracy across epochs.

## 🛠️ Tech Stack
* **Deep Learning Framework:** PyTorch / Keras *(Ajusta esto a la librería que usaste)*
* **Computer Vision & Data:** Torchvision / NumPy
* **Visualization:** Matplotlib

## 📈 Results vs. Baseline
*(Note: Replace the placeholders below with your actual results. Upload a screenshot of your Loss/Accuracy curves)*
![CNN Training Curves](link-to-your-image-here)

* **CNN Final Accuracy:** XX%
* **Improvement over MLP:** This architecture achieved a +XX% accuracy increase compared to the baseline dense network, converging faster with less overfitting.

## ⚙️ How to Run
Open the Jupyter Notebook `CNN_CIFAR10_Practica_Extendida.ipynb` and run the cells sequentially to initialize the dataset, train the CNN, and output the evaluation metrics.
