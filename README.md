# Lung Segmentation using U-Net with PSO Optimization

This project implements automated lung segmentation from chest X-ray images using the U-Net deep learning architecture, combined with Particle Swarm Optimization (PSO) for hyperparameter tuning. The goal is to generate accurate lung masks that can support downstream medical analysis and diagnostic pipelines.

---

## 📌 Project Overview

Lung segmentation is a fundamental preprocessing step in medical imaging. Traditional rule-based segmentation methods often fail on low-contrast X-rays or disease-affected regions. To address this challenge, this project uses:

- **U-Net** for biomedical image segmentation  
- **Dice Coefficient & IoU** as evaluation metrics  
- **Custom Data Generator** for loading X-ray images and masks  
- **Particle Swarm Optimization (PSO)** to explore hyperparameters including:
  - Learning rate  
  - Batch size  
  - Number of filters  
  - Dropout rate  

The baseline U-Net model achieves strong segmentation performance, while PSO provides insights into model behavior through rapid hyperparameter exploration.

---

## 🧠 Key Features

- Custom U-Net implementation with encoder–decoder blocks  
- Dice and Jaccard (IoU) metrics for segmentation evaluation  
- Streamlit application for model inference  
- PSO-based hyperparameter optimization  
- Visualizations comparing baseline vs PSO results  
- Training curves, scatter plots, and optimization trend graphs 
