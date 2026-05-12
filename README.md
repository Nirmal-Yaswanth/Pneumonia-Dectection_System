# 🫁 PNEUMONIA DETECTION FROM CHEST X-RAY IMAGES USING DEEP LEARNING MODELS


## 🚀 Project Overview

### Problem Statement

Pneumonia is one of the leading causes of respiratory-related deaths worldwide, particularly among children and elderly patients. Diagnosis using chest X-ray imaging requires expert radiological interpretation, which may not always be available in resource-limited healthcare environments.

Manual analysis may also introduce delays and observer variability. Therefore, this project proposes an **Artificial Intelligence–based automated diagnostic assistant** capable of detecting pneumonia from chest X-ray images while providing visual explanations using Grad-CAM to improve transparency and clinical trust.

---

### Key Objective

The primary objective of this project is to develop an **Explainable Artificial Intelligence (XAI) based pneumonia detection system** using deep learning techniques capable of accurately classifying chest X-ray images as:

* Normal
* Pneumonia

The system achieves approximately **95%+ diagnostic accuracy** while generating Grad-CAM heatmaps that highlight lung regions influencing predictions, improving interpretability for medical practitioners.

---

## 📊 Dataset Information

### Dataset Used

Chest X-ray Pneumonia Dataset (Kermany Dataset)

**Kaggle Source:**
https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia

### Description

The dataset contains pediatric chest X-ray images categorized into:

* Normal
* Pneumonia

Dataset Characteristics:

* Approximately **5,800+ X-ray images**
* Organized into training, validation, and testing folders
* Clinically labeled medical images

Additional Improvements:

* Added **700 Normal images** to reduce class imbalance
* Dataset split using **70–15–15 rule**

  * Training
  * Validation
  * Testin
