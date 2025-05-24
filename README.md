# 🐦 Image Compression using KMeans Clustering

> Compressing a Kingfisher bird image by reducing the number of colors using unsupervised learning.

---

## 📌 Overview

This project demonstrates how **KMeans clustering** can be used for **image compression** by reducing the number of colors in an image. The chosen image is of a vibrant **Kingfisher bird**, which is clustered in RGB space to produce compressed versions of the image using fewer colors (e.g., 4, 8, 16, 32).

---

## 🔍 Key Features

- ✅ Load and preprocess a high-resolution image
- ✅ Apply **KMeans** clustering to RGB pixel values
- ✅ Reconstruct compressed images from clustered colors
- ✅ Visualize side-by-side comparisons for different `K` values
- ✅ Plot clusters in **3D RGB space** for color understanding

---

## 🧠 How It Works

1. **Load the Image**  
   The Kingfisher image is loaded and reshaped into a 2D array of RGB pixels.

2. **Apply KMeans**  
   Clustering groups similar RGB values into `K` clusters using scikit-learn.

3. **Compress by Replacing Colors**  
   Each pixel is replaced by its cluster's centroid color.

4. **Reshape to Image Dimensions**  
   The modified pixel array is reshaped to the original image size.

---

## 🧪 Technologies Used

- Python 3
- NumPy
- Matplotlib
- scikit-learn
- OpenCV (for image I/O)

---
