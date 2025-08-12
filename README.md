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

## How to Run

1. **Clone the repository**
```bash
git clone https://github.com/adeiturrate/TFM.git
cd TMF
````

2. **Set up the environment**

The project comes with a requirements.txt file that includes all Python libraries and their versions used during development.
Create and activate a virtual environment, then install everything with
```bash
python -m venv .venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate
pip install -r requirements.txt
```
3. **Run the notebook**
```bash
jupyter notebook TFM.ipynb
```

4. **Configure dataset paths**
   
Before running all cells, update the dataset paths inside the notebook to match where your dermoscopic images and labels are stored locally.

5. **Execute cells**

Run the notebook cells in order to:

- Load and preprocess the dataset

- Train CNN and/or FSL models

- Evaluate performance and visualize results
