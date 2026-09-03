# Final-Project-UAS-of-Digital-Image-Processing-Course
Comparative analysis of Supervised (CNN, MobileNetV2) and Unsupervised (K-Means, Autoencoders) algorithms for image classification and clustering. Final Exam Project for Digital Image Processing.

# Comparative Analysis of Deep Learning Algorithms for Image Classification and Clustering

## 📌 About The Project
This repository contains the final exam project for the **Citra Digital (Digital Image Processing)** course. The project conducts a systematic, side-by-side comparison of deep learning algorithms applied to two distinct image recognition paradigms: Supervised and Unsupervised Learning.

The goal is to provide empirical evidence supporting algorithm selection under different data availability and computational constraints.

### 👥 Group 4 Members:
* Bandar Qaid Ahmed Abdulrab
* Fadilah
* Cahyo
* [Name 4] 
* [Name 5] 

## 📊 Datasets & Methodology
The experiment is divided into two main axes:

**1. Supervised Learning (Multi-class Car Brand Classification)**
* **Dataset:** Cars Image Dataset (Kaggle)
* **Algorithms Compared:** 
  * Custom Convolutional Neural Network (CNN) built from scratch.
  * Transfer Learning utilizing pre-trained **MobileNetV2**.
* **Objective:** Benchmark accuracy, precision, recall, and F1-score over a 10-epoch training schedule.

**2. Unsupervised Learning (Image Clustering)**
* **Dataset:** STL-10 Animal Image Dataset (5,000 images, 10 clusters)
* **Algorithms Compared:** 
  * Traditional K-Means clustering on flattened raw pixel vectors.
  * Convolutional Autoencoder combined with K-Means clustering.
* **Objective:** Evaluate cluster quality using the Silhouette Score and Davies-Bouldin Index.

## 🏆 Key Findings
* **Supervised Experiment:** Transfer Learning (MobileNetV2) substantially outperformed the Custom CNN. By leveraging ImageNet pre-trained feature representations, MobileNetV2 achieved significantly higher accuracy and generalization with limited training data.
* **Unsupervised Experiment:** Under a constrained training budget (5 epochs), raw-pixel K-Means outperformed the Autoencoder-enhanced K-Means. The findings highlight that the benefits of autoencoder-based feature extraction are contingent on sufficient training to produce a well-organized, semantically structured latent space.

## 📁 Project Assets
To view the full presentation and demonstration of this project, please access the files below:

* **[📄 Read the Full Research Article (PDF/Docx)](Link_to_your_Gdrive_Document)**
* **[🖥️ View the Presentation Slides (PPTX)](Link_to_your_Gdrive_PPTX)**
* **[🎬 Watch the Project Video Demonstration](Link_to_your_Gdrive_Video)**

## 💻 Tech Stack
* Python 3
* TensorFlow 2 / Keras
* Scikit-Learn
* OpenCV
* Seaborn / Matplotlib
