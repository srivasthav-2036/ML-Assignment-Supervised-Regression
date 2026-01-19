# Pixel Coordinate Prediction using Deep Learning

## Overview
This project solves a supervised regression problem using deep learning.  
Given a **50×50 grayscale image** that contains exactly **one bright pixel (value 255)** and all other pixels as zero, the task is to **predict the (x, y) coordinates** of that bright pixel.

A **Convolutional Neural Network (CNN)** is used to learn the spatial position of the pixel from the image.

---

## Problem Statement
- Input: 50×50 grayscale image  
- Condition: Only one pixel has value 255, others are 0  
- Output: (x, y) coordinates of the bright pixel  
- Method: Deep Learning (Supervised Regression)

---

## Approach Summary
- A synthetic dataset is generated because the pixel position is random and known.
- Images and coordinates are normalized for better training.
- A CNN is used to extract spatial features from the image.
- The model predicts continuous (x, y) values using a regression output layer.
- Model performance is analyzed using loss curves and coordinate plots.

---

## Files in this Repository
- `Pixel_Coordinate_Prediction_CNN.ipynb`  
  Contains dataset generation, model training, evaluation, and visualizations.
- `Pixel_Coordinate_Prediction_Explanation.pdf`  
  Detailed explanation of the approach and design choices.
- `requirements.txt`  
  List of required Python libraries.

---

## How to Run
```bash
pip install -r requirements.txt
jupyter notebook Pixel_Coordinate_Prediction_CNN.ipynb
