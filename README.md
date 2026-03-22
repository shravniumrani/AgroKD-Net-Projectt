# 🌱 AgroKD-Net: Efficient Crop & Weed Detection using Knowledge Distillation

![Python](https://img.shields.io/badge/Python-3.8-blue)
![YOLO](https://img.shields.io/badge/YOLOv8-Detection-green)
![Status](https://img.shields.io/badge/Status-Completed-success)
![License](https://img.shields.io/badge/License-MIT-yellow)

---

## 📌 Overview
AgroKD-Net is a lightweight object detection framework designed for real-time agricultural applications. It leverages Knowledge Distillation to transfer knowledge from a high-capacity YOLOv8 teacher model to a compact student model, improving efficiency without sacrificing accuracy.

## 🧠 Methodology

The AgroKD-Net model combines YOLO-based object detection with knowledge distillation.

- Teacher Model: High accuracy model
- Student Model: Lightweight model
- Distillation helps improve performance while reducing computation

The model is optimized for real-time agricultural applications.

---

## 🚀 Features
- Real-time object detection
- Lightweight and efficient model
- Suitable for edge devices and drones
- Handles small object detection

---

## 📊 Results

### 🔹 Model Comparison
| Model | mAP | Precision | Recall | Inference Time (ms) |
|------|-----|----------|--------|---------------------|
| YOLOv5 | 0.82 | 0.85 | 0.83 | 150 |
| YOLOv7 | 0.85 | 0.87 | 0.86 | 180 |
| MobileNet-SSD | 0.78 | 0.80 | 0.79 | 210 |
| EfficientDet | 0.86 | 0.88 | 0.87 | 220 |
| Faster R-CNN | 0.88 | 0.89 | 0.88 | 600 |
| AgroKD-Net | 0.87 | 0.90 | 0.89 | 160 |

---

## 📂 Dataset

The dataset consists of crop and weed images collected from agricultural fields.

- Total Images: ~2000+
- Classes: Crop, Weed
- Data split: Train / Validation / Test

This dataset helps the model learn to distinguish between crops and unwanted weeds.

## 📷 Outputs

### 🧠 Confusion Matrix
![Confusion Matrix](outputs/confusion_matrix.png)

### 📈 Precision-Recall Curve
![PR Curve](outputs/precision_curve.png)

### 📊 Model Comparison
![Model Comparison](outputs/model_comparison.png)

### 🔍 Qualitative Results
![Detection Results](outputs/qualitative_results.png)

### ⚖️ Teacher vs Student
![Comparison](outputs/teacher_vs_student.png)

## 🔬 Results Visualization

| Teacher Model | Student Model |
|--------------|--------------|
| ![](outputs/teacher_vs_student.png) | ![](outputs/qualitative_results.png) |

## 📂 Files Included
- Research Paper (PDF)
- Model Weights (.pt)
- Result Images

---

## 📌 Notebook (Implementation)
Due to file size limitations, the full implementation is available here:

👉 https://colab.research.google.com/drive/1elVBfgaHhIq5umEBpOBnCwNPbzeI3Xel?usp=sharing

---

## 🚀 Key Highlights

- Lightweight YOLOv8-based student model
- Knowledge Distillation for performance boost
- Handles class imbalance in agricultural datasets
- Real-time deployment ready
- Supports quantization (FP32 → INT8)

## ⚙️ How to Run
1. Open the Colab notebook
2. Run all cells
3. Model will perform detection

---

## 🎯 Applications
- Smart Farming
- Drone-based Monitoring
- Automated Weed Control

## 📌 Future Work

- Mobile deployment (Android/iOS)
- Edge device optimization (Jetson Nano)
- Real-time drone-based weed detection
- 
- ## 📌 Conclusion

AgroKD-Net achieves a balance between accuracy and efficiency, making it suitable for real-time deployment in smart farming systems.

It performs well compared to traditional object detection models while maintaining lower computational cost.


