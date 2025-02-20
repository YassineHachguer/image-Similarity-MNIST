
# 🖼️ Image Recognition using K-NN and Histogram of Oriented Gradients (HOG)

This project implements an image recognition system using the **K-Nearest Neighbors (K-NN)** algorithm combined with the **Histogram of Oriented Gradients (HOG)** descriptor for feature extraction. The system processes, analyzes, and recognizes images based on feature similarity.  

## 📌 Table of Contents
- [Overview](#overview)  
- [Features](#features)  
- [Installation](#installation)  
- [Usage](#usage)  
- [Dataset](#dataset)  
- [Skills Utilized](#skills-utilized)  

## 🔍 Overview  
The image recognition system extracts **HOG features** from images to create a vector representation that captures key gradient and edge patterns. Using **Euclidean distance**, the K-NN algorithm identifies and retrieves the most similar images from the dataset.  

## 🚀 Features  
✔ **Image Pre-processing**: Filtering and normalizing images for consistency.  
✔ **Feature Extraction**: Using HOG descriptors to represent gradient structures.  
✔ **Image Similarity Calculation**: Measuring similarity using Euclidean distance.  
✔ **Visualization**: Displaying query images alongside the most similar matches.  

## ⚙️ Installation  
1️⃣ **Clone this repository**:  
   ```sh
   git clone <repository_url>
   cd <repository_folder>
   ```  
2️⃣ **Install dependencies**:  
   ```sh
   pip install numpy scipy matplotlib scikit-image
   ```  

## ▶️ Usage  
1. Prepare your image dataset by organizing it into **training** and **testing** folders.  
2. Ensure images are pre-processed (filtered and normalized).  
3. Run the script to classify images and visualize results.  

## 🗂 Dataset  
- The dataset should be structured into separate folders for training and testing images.  
- Pre-processing ensures uniformity and optimal feature extraction.  

## 🛠 Skills Utilized  
📌 **Image Processing & Feature Extraction**: Using **HOG** to generate feature descriptors.  
📌 **Data Cleaning & Pre-processing**: Applying filtering and normalization techniques.  
📌 **Data Visualization**: Displaying similar images with **Matplotlib**.  
📌 **Python Libraries**: Hands-on experience with **NumPy, SciPy, and scikit-image** for image processing.  
