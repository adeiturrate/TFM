# TFM: Skin Lesion Classification with Machine Learning

Automated classification of skin lesions from dermoscopic images using **Convolutional Neural Networks (CNNs)** and **Few-Shot Learning (FSL)**.

> **Goal:** Address class imbalance and limited data availability, with a focus on improving detection of underrepresented classes such as **DF** (dermatofibroma) and **VASC** (vascular lesions).

---

## Overview
This project compares traditional CNN architectures (Simple CNN, InceptionV3, EfficientNet-B3) and a FSL approach using **Prototypical Networks** for multiclass skin lesion classification.

- **CNN Models:** Simple CNN, InceptionV3, EfficientNet-B3  
- **FSL Approach:** Prototypical Networks (episodic training)  
- **Metrics:** accuracy, balanced accuracy, macro/micro F1-score, class-wise AUC  
- **Techniques:** rescaling, normalization, data augmentation, class-weighted sampling

---
