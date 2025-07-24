# SHOE-IMAGE_DETECTION



# 🧠 Deep Learning Image Detection Project (NIKE vs ADIDAS Logo Classification)

## 📌 About the Project

This deep learning project focuses on building an image classification model using Convolutional Neural Networks (CNN) to distinguish between **NIKE** and **ADIDAS** logos. The dataset consists of images of both brand logos organized into folders. The model is trained on grayscale images and uses TensorFlow and Keras to learn the visual differences between the two brands.

Key points:
- Custom image dataset of brand logos
- CNN architecture with Conv2D, MaxPooling, Flatten, Dense, and Dropout layers
- Google Colab used for training and testing
- Model reshapes input images to fit CNN input format: `(IMG_SIZE, IMG_SIZE, 1)`
- Provides accuracy and loss graphs to evaluate performance
- Makes predictions on unseen test images

---

## 🚀 Project Overview

- **Model Type:** Convolutional Neural Network (CNN)
- **Dataset:** Custom NIKE vs ADIDAS logo images
- **Frameworks Used:** TensorFlow, Keras
- **Language:** Python
- **Notebook Environment:** Google Colab

---

## 🔍 Features

- Image preprocessing using PIL and NumPy
- Training CNN with Conv2D, MaxPooling, Flatten, Dense layers
- Visualizing training loss and accuracy
- Making predictions on test images
- Reshape logic: `.reshape(-1, IMG_SIZE, IMG_SIZE, 1)` to prepare input for CNN
- Final model trained and tested for binary classification

---

## 🛠️ Tech Stack

- Python  
- TensorFlow / Keras  
- NumPy  
- Matplotlib  
- PIL  
- Google Colab  

---

## 🧪 How to Run

1. Upload your dataset to Google Drive in the specified folder format.
2. Mount the drive in the Colab notebook.
3. Run the training cells in the notebook.
4. Predict using test images.
5. Visualize output and metrics.

---

## 📌 Use Cases

- Brand logo detection in marketing
- Image classification practice for deep learning beginners
- Custom object classification projects

---

## 🙋‍♂️ Author

Anantha Omprakash  
(Feel free to reach out for collaboration or suggestions)

---

## 📄 License

This project is for educational purposes only.


