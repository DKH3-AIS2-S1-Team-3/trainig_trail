# Garbage Classification using YOLOv8s (Trial Version)

## Description
This repository contains a trial version of a garbage classification model using YOLOv8. 
The model is trained on a small subset of the dataset with augmentation, and the accuracy is limited. 
This version is intended for demonstration and instructor review purposes.

---

## Repository Contents
- `notebook.ipynb` - Kaggle notebook with data preprocessing, augmentation, and YOLOv8 training.
- `README.md` - This file.

---

## 🛠 Required Libraries

Before running the notebook, make sure to install the following libraries:

```bash
pip install ultralytics albumentations opencv-python-headless


Usage
1. Clone the repository:

git clone <https://github.com/DKH3-AIS2-S1-Team-3/trainig_trail>
2. Open and run the notebook.ipynb in Kaggle, Google Colab, or Jupyter Notebook to see:
    * Dataset preprocessing
    * Data augmentation
    * YOLOv8 training



Notes
* This is a trial model. Accuracy is currently low:
    * Training mAP50: ~41%
    * Validation mAP50: ~24%
* Training was limited to a small subset of augmented images .
* The model might overfit due to small dataset size.
* Future improvements will include:
    * Training on the full dataset
    * Hyperparameter tuning
