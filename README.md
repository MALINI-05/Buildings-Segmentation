# 🏙️ Building Segmentation using U-Net – Satellite Imagery

This project implements a **U-Net-based semantic segmentation model** to detect and segment **building footprints** in satellite images.  
The model performs pixel-wise classification to accurately outline urban structures for use in land cover analysis, urban planning, and mapping.

---

## 🎯 Objective

- Input: RGB satellite images  
- Output: Binary segmentation mask indicating building pixels  
- Goal: Automatically detect and segment buildings from overhead imagery using deep learning

---

## 🛰️ Dataset

- Source: Aerial or satellite RGB images  
- Ground Truth: Binary masks indicating building locations  
- Preprocessed to 256×256 pixel patches

---

## 🧠 Model Architecture

- U-Net architecture with encoder–decoder structure  
- Convolutional + MaxPooling layers for feature extraction  
- Transposed convolutions for upsampling  
- Output layer with sigmoid activation for binary segmentation

---

## 📁 Project Structure

