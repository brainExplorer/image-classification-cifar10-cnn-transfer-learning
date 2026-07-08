# 🧠 Image Classification Journey: CIFAR-10, CNN & Transfer Learning

This repository is part of my ongoing Machine Learning learning journey.

Rather than simply training a model and moving on, I wanted to understand **how modern image classification pipelines are built**, why certain architectural decisions are made, and how different training strategies affect performance.

The notebook documents the complete workflow from a custom CNN implementation to Transfer Learning using ResNet-18 while keeping the focus on experimentation, reproducibility, and code readability.

---

## 📚 What this project covers

* Loading and preprocessing the CIFAR-10 dataset
* Building a Convolutional Neural Network (CNN) from scratch
* Understanding convolution, pooling, and Batch Normalization
* Designing a lightweight CNN architecture
* Implementing a reusable training pipeline
* Monitoring training and validation performance
* Evaluating classification accuracy
* Transfer Learning with ResNet-18
* Comparing Feature Extraction vs Fine-Tuning
* Visualizing training history
* Reproducibility practices for PyTorch projects

---

## 🧠 Topics explored

This project is less about obtaining the highest possible accuracy and more about understanding the engineering decisions behind modern computer vision models.

Some of the concepts explored include:

* CNN architecture design
* Batch Normalization
* Global Average Pooling
* Transfer Learning
* Feature Extraction
* Fine-Tuning
* Learning Rate strategies
* Training loops
* Validation workflow
* Model comparison
* Performance visualization
* Reproducible experiments

---

## 📈 Expected comparison

| Model                          | Expected Accuracy |
| ------------------------------ | ----------------: |
| Custom CNN                     |           ~75–80% |
| ResNet-18 (Feature Extraction) |           ~85–88% |
| ResNet-18 (Fine-Tuning)        |           ~92–94% |

The goal is to understand **why** these models perform differently rather than only comparing the final accuracy numbers.

---

## 📂 Project Structure

```
Image_Classification_Project/
│
├── Image_Classification_Project_CIFAR_10_to_CNN_and_Transfer_Learning_Comparison.ipynb
├── README.md
└── requirements.txt
```

---

## 🚀 Technologies

* Python
* PyTorch
* TorchVision
* NumPy
* Matplotlib

---

## 🎯 Learning Objectives

This repository helped me better understand:

* how convolutional neural networks extract visual features
* the practical differences between training from scratch and Transfer Learning
* how pretrained models can significantly improve performance on relatively small datasets
* how to organize deep learning experiments into reusable and maintainable code

---

## 🔄 What's Next

This repository is intentionally designed as an evolving study notebook.

Future improvements include:

* Compare with EfficientNet-B0
* Grad-CAM visualization
* Hyperparameter tuning (Optuna)
* Multi-GPU training (DDP)
* ONNX / TorchScript export
* TensorBoard integration
* Additional data augmentation experiments

---

## 💡 About this repository

This is not intended to be a production-ready image classification project.

Instead, it represents another step in my ongoing journey of learning Machine Learning and Deep Learning through hands-on implementation, experimentation, and continuous improvement.

Each repository I publish builds upon the previous one as I continue exploring new algorithms, architectures, and best practices.
