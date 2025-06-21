# 🌌 Galaxy Morphology Classification using CNN & LeNet

> 🚀 A Deep Learning project to classify galaxy images into 10 morphological classes using CNN and LeNet-5 on the Galaxy10 AstroNN SDSS dataset.  


---

## 📘 Abstract

Galaxies vary in shape and structure, and studying their **morphology** is crucial for understanding the **evolution of the universe**. 🪐  
This project uses **Convolutional Neural Networks (CNN)** and **LeNet-5** to classify galaxy images from the **Galaxy10 AstroNN SDSS** dataset.  
✨ Results show LeNet-5 outperformed CNN with an accuracy of **92%** versus **72%**.

---

## 🎯 Objective

- 🛰️ Automatically classify galaxies based on morphology
- 🧠 Apply deep learning models (CNN and LeNet)
- 📈 Compare performance metrics (accuracy, confusion matrix, etc.)
- 🗃️ Use AstroNN’s Galaxy10 SDSS dataset for training & testing

---

## 🧠 Methodology

1. 🔽 **Dataset**: Galaxy10 from AstroNN Image Datasets
2. ⚙️ **Preprocessing**: Resize, normalize, one-hot encoding, data split (85% train / 15% test)
3. 🧱 **Model 1 – CNN**:
   - Conv2D → MaxPooling → Dense Layers
   - Accuracy: **72%**
4. 🧱 **Model 2 – LeNet-5**:
   - Conv2D → AveragePooling → Dense Layers
   - Accuracy: **92%**
5. 📊 **Evaluation**:
   - Accuracy & Loss plots
   - Confusion Matrix
   - Summary & Comparison

---

## 🛠️ Tech Stack

| Tool/Library | Purpose |
|--------------|---------|
| 🐍 Python | Programming Language |
| 📦 TensorFlow / Keras | Neural Network Framework |
| 🧪 Google Colab | Training Environment |
| 📚 AstroNN | Dataset access & utilities |
| 📊 Matplotlib, Seaborn | Visualization |
| 🧮 Scikit-learn | Evaluation metrics |
