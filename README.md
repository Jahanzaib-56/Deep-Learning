<div align="center">

<!-- Banner -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=200&section=header&text=Deep%20Learning%20Lab&fontSize=52&fontColor=ffffff&fontAlignY=38&desc=Computer%20Vision%20%7C%20Neural%20Networks%20%7C%20Autonomous%20Systems&descAlignY=58&descColor=a78bfa" width="100%"/>

# 🧠 Deep Learning Lab

**A curated collection of Deep Learning & Computer Vision projects** — from foundational CNNs to production-ready pipelines, built with a focus on autonomous driving and intelligent perception systems.

[![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![PyTorch](https://img.shields.io/badge/PyTorch-2.x-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)](https://pytorch.org)
[![OpenCV](https://img.shields.io/badge/OpenCV-4.x-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)](https://opencv.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-22c55e?style=for-the-badge)](LICENSE)

</div>

---

## 👤 About

I'm **MJay**, a 6th-semester AI & Computer Science student (distance learning) at **Virtual University of Pakistan**, specializing in **Computer Vision** and **Machine Learning** with a focus on **Autonomous Driving** and **Robotics Perception**.

This repository is my hands-on lab — every project here reflects real learning, real experiments, and a long-term goal of contributing to perception systems for autonomous vehicles.

> 🎯 **Research Interests:** BEVFusion · Sensor Fusion · LiDAR-Camera Perception · Real-time Object Detection · Traffic Scene Understanding

---

## 📁 Repository Structure

```
deep-learning-lab/
│
├── 📂 computer-vision/
│   ├── gtsrb-traffic-sign-classifier/     # CNN-based 43-class traffic sign recognition (FYP)
│   └── ...
│
├── 📂 classification/
│   └── ...
│
├── 📂 object-detection/
│   └── ...
│
├── 📂 transfer-learning/
│   └── ...
│
├── 📂 notebooks/
│   └── exploratory/                       # Experiments, ablations, concept demos
│
└── 📂 utils/
    └── ...                                # Shared transforms, metrics, visualization helpers
```

---

## 🚀 Projects

### 🔴 Featured

| Project | Description | Dataset | Tech | Status |
|--------|-------------|---------|------|--------|
| [GTSRB Traffic Sign Classifier](./computer-vision/gtsrb-traffic-sign-classifier) | End-to-end CNN pipeline for 43-class German traffic sign recognition. Includes transfer learning (ResNet50/EfficientNet), Optuna hyperparameter tuning, and a Streamlit demo. | [GTSRB](https://benchmark.ini.rub.de/gtsrb_dataset.html) | PyTorch · Optuna · Streamlit | 🟡 In Progress |

---

### 🟢 Completed

> Projects will be listed here as they reach a complete, documented state.

---

### 🔵 Planned / Upcoming

| Project | Description | Key Concepts |
|--------|-------------|--------------|
| YOLOv8 Custom Detector | Fine-tune YOLOv8 on a custom dataset, export to ONNX, and serve via FastAPI | Transfer Learning · ONNX · REST API |
| Customer Segmentation (K-Means) | Unsupervised clustering for customer behavior analysis with visual cluster profiling | K-Means · PCA · Scikit-learn |
| Lightweight CNN Comparison | Benchmark LeNet / AlexNet / ResNet / MobileNet on GTSRB; target arXiv/IEEE Access publication | Architecture Search · Reproducibility |

---

## 🛠️ Tech Stack

| Layer | Tools |
|-------|-------|
| **Framework** | PyTorch 2.x |
| **CV** | OpenCV, Torchvision, Albumentations |
| **Experiment Tracking** | Optuna, (MLflow — planned) |
| **Deployment** | Streamlit, FastAPI, Hugging Face Spaces |
| **Data & Analysis** | NumPy, Pandas, Matplotlib, Seaborn |
| **Version Control** | Git, GitHub |

---

## ⚡ Quick Start

```bash
# 1. Clone the repository
git clone https://github.com/<your-username>/deep-learning-lab.git
cd deep-learning-lab

# 2. Create a virtual environment
python -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate

# 3. Install base dependencies
pip install -r requirements.txt

# 4. Navigate to any project and follow its own README
cd computer-vision/gtsrb-traffic-sign-classifier
```

> Each project folder contains its own `README.md` with dataset setup instructions, training commands, and evaluation results.

---

## 📊 Learning Roadmap

```
✅ CNN Fundamentals (AlexNet → DenseNet)
✅ Transfer Learning & Fine-tuning
✅ PyTorch Autograd & Custom Training Loops
✅ Hyperparameter Optimization (Optuna)
🟡 Experiment Tracking (MLflow / W&B)
🟡 Object Detection (YOLOv8)
⬜ ONNX Export & Model Serving
⬜ Sensor Fusion Basics (LiDAR + Camera)
⬜ Bird's Eye View Representations (BEV)
```

---

## 📚 Reference Papers

Papers that directly influence the work in this repository:

- **AlexNet** — Krizhevsky et al., 2012 — *ImageNet Classification with Deep CNNs*
- **ResNet** — He et al., 2015 — *Deep Residual Learning for Image Recognition*
- **EfficientNet** — Tan & Le, 2019 — *EfficientNet: Rethinking Model Scaling*
- **YOLOv8** — Jocher et al., 2023
- **BEVFusion** — Liu et al., 2022 — *Multi-Task Multi-Sensor Fusion with BEV*
- **Attention Is All You Need** — Vaswani et al., 2017 *(in study)*

---

## 🤝 Connect

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/<your-profile>)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/<your-username>)
[![Hugging Face](https://img.shields.io/badge/HuggingFace-Spaces-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)](https://huggingface.co/<your-username>)

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=100&section=footer" width="100%"/>

*Building toward intelligent perception — one model at a time.*

</div>
