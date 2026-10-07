# Hi, I'm Wilgo 👋

**Computer Vision Engineer · PhD Researcher @ University of Coimbra · Open to Remote Roles**

> Building computer vision systems for real-world data: segmentation, object detection, model calibration, and deployment.  
> 3 peer-reviewed papers · 55 citations · h-index 4

---

## 🔬 What I work on

- **Semantic segmentation** of RGB and multispectral imagery
- **Object detection** with YOLO for real-world visual inspection tasks
- **Model calibration**, uncertainty estimation, and confidence analysis
- **Computer vision evaluation & failure analysis**
- **Production CV pipelines** with FastAPI, Docker, and MLflow
- Remote sensing for precision agriculture and structural/infrastructure monitoring

---

## 🛠️ Tech Stack

**Deep Learning & Computer Vision**  
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![Ultralytics](https://img.shields.io/badge/Ultralytics_YOLO-111F68?style=flat)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)

**MLOps & Deployment**  
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat&logo=mlflow&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

**Data & Analysis**  
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=flat&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)

---

## 🚀 Featured Projects

### [road-damage-detection](https://github.com/wilgomoreira/road-damage-detection)
> Object detection pipeline for road-surface damage using YOLO11

- Detection of **Pothole, Crack, and Manhole**
- Leakage-aware temporal dataset splitting for sequential road imagery
- YOLO11 training and controlled experiments on model size, image resolution, and Mosaic augmentation
- Detailed failure analysis by class, object size, acquisition session, and confidence
- Manual annotation audit and class-specific confidence threshold optimization
- Best configuration: **YOLO11n @ 960 px**
- Final test performance: **mAP50 0.348 · mAP50-95 0.176**

---

### [segmentation-api](https://github.com/wilgomoreira/segmentation-api)
> Production-ready binary semantic segmentation pipeline

- U-Net from scratch with skip connections
- BCEWithLogitsLoss · IoU · Dice
- FastAPI inference endpoint
- Docker containerization
- MLflow experiment tracking
- Dataset: Carvana, 5,088 images
- PyTorch · Python 3.10

---

### [multispectral-vineyard-segmentation](https://github.com/wilgomoreira/multispectral-vineyard-segmentation)
> ROBOT24 · IEEE · Oral Presentation

- Evaluated SegNet and DeepLabV3 across train-test, k-fold, and group k-fold splits
- RGB · NDVI · GNDVI · Early Fusion modalities on 3 real vineyard datasets
- Key finding: group k-fold exposes generalization gaps that random splits hide

---

### [crf-multispectral-segmentation](https://github.com/wilgomoreira/crf-multispectral-segmentation)
> IbPRIA25 · Springer · Oral Presentation

- Spatial dense CRF post-processing with Bayesian-optimized parameters
- Applied on logits from SegNet and DeepLabV3
- Best result: 85.85% average F1
- Model-agnostic refinement layer

---

### [probabilistic-image-segmentation](https://github.com/wilgomoreira/probabilistic-image-segmentation)
> ICIR24 · IEEE · Poster Presentation

- KDE as a non-parametric alternative to sigmoid for probability estimation
- Improved Expected Calibration Error compared with sigmoid baseline
- Multispectral vineyard imagery
- SegNet · DeepLabV3

---

## 📄 Publications

| Year | Title | Venue | Type |
|------|-------|-------|------|
| 2026 | C2F-SL: A Calibrated Cascade Framework for Soft Label Generation in Multispectral Segmentation | ICIST26, IEEE | Oral |
| 2025 | A Spatial Dense CRF Framework for Post-Processing in Multispectral Image Segmentation | IbPRIA25, Springer | Oral |
| 2024 | Multispectral Image Segmentation in Agriculture: Evaluating DL Models with Train-Test Split and Cross-Validation | ROBOT24, IEEE | Oral |
| 2024 | A Probabilistic Framework Applied to Multispectral Image Segmentation | ICIR24, IEEE | Poster |

📊 **55 citations · h-index 4** · [Google Scholar](https://scholar.google.com/citations?user=wpU67h8AAAAJ&hl=en)

---

## 📈 GitHub Activity

Selected repositories focus on:

- Computer Vision
- Semantic Segmentation
- Object Detection
- Model Calibration
- Deep Learning
- MLOps

![GitHub Streak](https://streak-stats.demolab.com?user=wilgomoreira&theme=dark&hide_border=true)

---

## 🎓 Background

PhD in Electrical Engineering · Intelligent Systems @ University of Coimbra (ISR-UC)

10+ years of professional engineering experience before transitioning into AI/ML research.

My work combines an engineering background with practical computer vision, deep learning research, model evaluation, and deployment.

---

## 📬 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/wilgomoreira)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:wilgomoreira@gmail.com)
[![Google Scholar](https://img.shields.io/badge/Google_Scholar-4285F4?style=flat&logo=google-scholar&logoColor=white)](https://scholar.google.com/citations?user=wpU67h8AAAAJ&hl=en)

---

*Open to remote Computer Vision Engineer and ML Engineer roles in Europe and globally.*
