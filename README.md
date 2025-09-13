Got it 👍
Here’s your cleaned-up **README.md** without the SDGs, Team Members, and Future Work sections:

---

# Leukemia Cell Classification Using Deep Learning

## 📌 Project Overview

Leukemia, a type of blood cancer affecting white blood cells, presents diagnostic challenges due to the morphological similarities between cancerous and healthy cells. Manual diagnosis via microscopy is often time-consuming and subject to observer variability.

This project introduces an **automated, deep learning-based image classification system** for leukemia detection. Using advanced convolutional neural network (CNN) and transformer architectures, the project demonstrates how AI can enhance early diagnosis and clinical decision-making.

---

## 🔬 Objectives

* Develop a reliable image-based classification system for leukemia cells.
* Compare deep learning and transfer learning models for multi-class classification.
* Evaluate model performance on accuracy, robustness, and generalization.
* Lay groundwork for future cloud-based diagnostic support tools.

---

## 📊 Dataset

* **Source**: Publicly available leukemia dataset from [Kaggle](https://www.kaggle.com/).
* **Size**: 3,261 original white blood cell images.
* **Classes**:

  * Benign
  * Early
  * Pre
  * Pro

Original images were prioritized over segmented ones to retain complete cellular morphology.

---

## 🧠 Models Used

* **VGG16** → Achieved best generalization with **96.32% test accuracy**.
* **ResNet50** → Very high accuracy (**99.85%**) but showed signs of overfitting.
* **EfficientNetB0** → **99.82% accuracy**, also overfitting tendencies.
* **Vision Transformer (ViT)** → **92.33% accuracy**, less robust than CNNs.

---

## 🚀 Key Findings

* **VGG16** proved the most reliable and generalizable among the tested models.
* Transfer learning significantly boosted performance across architectures.
* Hybrid approaches and segmentation integration present future opportunities.

---

## ⚙️ Tech Stack

* **Python**
* **TensorFlow / Keras**
* **NumPy, Pandas, Matplotlib**
* **Jupyter Notebook**

---

## 📜 License

This project is released for academic and research purposes. Feel free to use, modify, and contribute while giving proper attribution.

---
