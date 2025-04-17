---
title: Pneumonia Prediction with Computer Vision
publishDate: 2025-04-17 00:00:00
img: /assets/computer-vision-banner.png
img_alt: X-ray image showing pneumonia infection
description: |
  A deep learning model was developed to predict the presence of pneumonia from chest X-ray images. The model uses TensorFlow, Keras, and image processing techniques to analyze medical images and assist healthcare professionals in early diagnosis.

tags:
 - Computer Vision
 - Pneumonia Detection
 - Deep Learning
---
## Pneumonia Detection with Computer Vision

> "The best way to predict the future is to invent it." — Alan Kay

Using **computer vision** techniques, we developed a model to predict pneumonia in patients by analyzing chest X-ray images. This method enhances the speed and accuracy of diagnosis, particularly in settings where radiologists may not be readily available.

### Data Collection

The dataset used for this project consists of chest X-ray images that were pre-processed using **Pillow** and **OpenCV**. The images were resized, normalized, and prepared for input into a **TensorFlow** model.

### Model Development

We built a **Convolutional Neural Network (CNN)** using **TensorFlow** and **Keras** to classify the images into pneumonia-positive or pneumonia-negative categories. The model was trained on a large dataset of labeled medical images to optimize its accuracy.

#### Results

- **Accuracy**: prediction accuracy on the test dataset
- **Tool used**: TensorFlow, Keras, Pillow, OpenCV

---

### Technologies utilisées

- **TensorFlow** : Pour la création et l'entraînement du modèle de deep learning.
- **Keras** : Pour simplifier l'implémentation du modèle CNN.
- **Pillow / OpenCV** : Pour la prétraitement des images médicales.
- **Matplotlib** : Pour visualiser les résultats et les performances du modèle.

