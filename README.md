# 🐶🐱 Cat vs Dog Image Classification with TensorFlow

This project demonstrates how to build a binary image classifier using Convolutional Neural Networks (CNNs) in TensorFlow/Keras. The model classifies images as either a **Cat** or a **Dog**.

## 📁 Dataset

- **Source**: [Kaggle - Cat and Dog Dataset](https://www.kaggle.com/datasets/bhavikjikadara/dog-and-cat-classification-dataset)
- **Path Used**: `/kaggle/input/dog-and-cat-classification-dataset/PetImages`
- The dataset contains two folders: `Cat` and `Dog`

## 📌 Features

- Image Preprocessing and Data Augmentation using `ImageDataGenerator`
- Corrupt image removal to avoid training errors
- CNN model with Conv2D, MaxPooling, Dropout, and Dense layers
- Binary classification (`sigmoid` activation)
- Real-time prediction from uploaded image in Google Colab

## 🧰 Requirements

Make sure the following Python packages are installed:

```bash
tensorflow
numpy
matplotlib
