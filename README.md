# Leukemia Cell Classification Using Deep Learning

<p align="center">
  <img src="https://img.shields.io/badge/Google%20Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white" />
  <img src="https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" />
  <img src="https://img.shields.io/badge/Numpy-013243?style=for-the-badge&logo=numpy&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white" />
  <img src="https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=plotly&logoColor=white" />
  <img src="https://img.shields.io/badge/Gradio-FF6F91?style=for-the-badge&logo=gradio&logoColor=white" />
</p>

## 📌 Project Overview
Leukemia, a type of blood cancer affecting white blood cells, presents diagnostic challenges due to the morphological similarities between cancerous and healthy cells. Manual diagnosis via microscopy is often time-consuming and subject to observer variability.  

This project introduces an **automated, deep learning-based image classification system** for leukemia detection. Using advanced convolutional neural network (CNN) and transformer architectures, the project demonstrates how AI can enhance early diagnosis and clinical decision-making.

## 🔬 Objectives
- Develop a reliable image-based classification system for leukemia cells  
- Compare deep learning and transfer learning models for multi-class classification  
- Evaluate model performance on accuracy, robustness, and generalization  
- Lay groundwork for future cloud-based diagnostic support tools  

## 📊 Dataset
- **Source**: [Blood Cell Cancer (ALL) 4-Class Dataset](https://www.kaggle.com/datasets/mohammadamireshraghi/blood-cell-cancer-all-4class)  
- **Size**: 3,261 original white blood cell images  
- **Classes**:  
  - Benign  
  - Early  
  - Pre  
  - Pro  

Original images were prioritized over segmented ones to retain complete cellular morphology.  

## 🧠 Models Used
- **VGG16** → Achieved best generalization with **96.32% test accuracy**  
- **ResNet50** → Very high accuracy (**99.85%**) but showed signs of overfitting  
- **EfficientNetB0** → **99.82% accuracy**, also overfitting tendencies  
- **Vision Transformer (ViT)** → **92.33% accuracy**, less robust than CNNs  

## 🚀 Key Findings
- **VGG16** proved the most reliable and generalizable among the tested models  
- Transfer learning significantly boosted performance across architectures  
- Hybrid approaches and segmentation integration present future opportunities  

## ⚙️ Tech Stack
- **Python**  
- **TensorFlow / Keras**  
- **NumPy, Pandas, Matplotlib**  
- **Jupyter Notebook**  
- **Gradio (for deployment UI)**  

## 📜 License
This project is released for academic and research purposes. Feel free to use, modify, and contribute while giving proper attribution.
```
