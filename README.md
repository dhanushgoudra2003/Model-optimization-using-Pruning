# 📊 Image Classification with Model Optimization (Pruning)

## 🚀 Overview

This project builds an efficient **image classification system** using **PyTorch**, combined with **image preprocessing** and **model pruning techniques** to optimize performance and reduce model size.

The pipeline covers the complete workflow:

* Image preprocessing
* Model training
* Model pruning (optimization)
* Model evaluation

---

## 🧠 Key Features

* Automated image preprocessing pipeline
* Structured dataset handling using ImageFolder
* Deep learning model training using PyTorch
* Model pruning for efficiency and compression
* Evaluation on unseen test data
* Modular and scalable design

---


## ⚙️ Tech Stack

* Python
* PyTorch
* Torchvision
* NumPy
* PIL (Python Imaging Library)

---


## 🧹 Preprocessing

The preprocessing pipeline includes:

* Resizing images to **224 × 224**
* Optional grayscale conversion
* Normalization for model compatibility

---

## 🏋️ Model Training

* Uses **PyTorch DataLoader** for batching
* Loss Function: **CrossEntropyLoss**
* Optimizer: **Adam / SGD**
* Supports GPU acceleration

---

## ✂️ Model Pruning (Optimization)

Model pruning is applied to:

* Reduce model size
* Improve inference speed
* Optimize deployment on low-resource devices

### Benefits:

* Faster predictions
* Lower memory usage
* Edge-device friendly

---

## 🧪 Model Evaluation

* Tested on unseen dataset
* Accuracy and performance metrics computed
* Supports single image prediction

---

## ▶️ How to Run

### 1. Install Dependencies

```bash
pip install torch torchvision numpy pillow
```

### 2. Run the Notebook

```bash
jupyter notebook
```

Open:

```
ML_code.ipynb
```

Run all cells step-by-step.

---

## 📈 Future Improvements

* Add training & validation graphs
* Use transfer learning (ResNet / MobileNet)
* Handle class imbalance (SMOTE / weighting)
* Build a web app (Flask / Streamlit)
* Convert model to ONNX / TensorRT

---

## 🎯 Use Cases

* Medical image classification
* Plant disease detection
* Industrial defect detection
* General multi-class classification problems

---

## 💡 Highlights

* End-to-end ML pipeline
* Optimization using pruning
* Practical and deployment-focused
* Strong real-world applicability
