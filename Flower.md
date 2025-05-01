---
title: "Flower Classification using Transfer Learning"
author: "Satya Penumatcha"
course: "CS672 – Introduction to Deep Learning"
university: "Pace University"
semester: "Spring 2025"
frameworks: ["TensorFlow", "PyTorch"]
dataset: "Flowers Recognition"
license: "Academic Use Only"
---

# 🌼 Flower Classification using Transfer Learning (CS672 Project 3)

This project demonstrates flower classification using transfer learning with TensorFlow and PyTorch. Pre-trained CNNs (MobileNetV2 and ResNet50) are fine-tuned on the Flowers Recognition dataset to classify flower species into five categories: daisy, dandelion, rose, sunflower, and tulip.

---

## 📁 Repository Structure

```
Flower-Classification-TransferLearning/
│
├── TensorFlow/
│   ├── tf_flower_classifier.ipynb
│   ├── model_tf.h5
│
├── PyTorch/
│   ├── torch_flower_classifier.ipynb
│   ├── model_torch.pth
│
├── data/
│   └── flowers/
│
├── results/
│   ├── confusion_matrix_tf.png
│   ├── confusion_matrix_torch.png
│   └── evaluation_report.txt
│
├── archive.zip
├── README.md
└── requirements.txt
```

---

## 🎯 Objectives

- Apply transfer learning on a flower classification task
- Fine-tune MobileNet and ResNet50 on a labeled dataset
- Use TensorFlow and PyTorch to compare frameworks
- Evaluate performance using multiple metrics

---

## 🔧 Setup Instructions

1. Clone the repository:
```bash
git clone https://github.com/your-username/Flower-Classification-TransferLearning.git
cd Flower-Classification-TransferLearning
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Download the [dataset](https://www.kaggle.com/datasets/alxmamaev/flowers-recognition) and extract it to `data/flowers/`.

---

## 🚀 Running the Project

### TensorFlow:
```bash
cd TensorFlow
jupyter notebook tf_flower_classifier.ipynb
```

### PyTorch:
```bash
cd PyTorch
jupyter notebook torch_flower_classifier.ipynb
```

---

## 📊 Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

All evaluation visuals and reports are stored under the `results/` folder.

---

## 📌 Features

- Pre-trained CNN models (MobileNetV2, ResNet50)
- TensorFlow and PyTorch implementation side-by-side
- Layer freezing and custom classifier head
- Structured workflow: data prep → training → evaluation
- Supports reproducibility with fixed seeds and organized outputs

---

## 🙋‍♂️ Author

**Satya Penumatcha**  
Graduate Student, MS in Data Science  
Pace University  
[LinkedIn](https://linkedin.com) | [GitHub](https://github.com/your-username)

---

## 📄 License

This repository is intended for academic use only under the CS672 Spring 2025 curriculum at Pace University.
