# NoPainNoTrain - Artificial Neural Networks and Deep Learning Projects

Welcome to the repository for the **NoPainNoTrain** group projects in the **Artificial Neural Networks and Deep Learning (AN2DL)** course. This repository contains the code and reports for two group assignments where we achieved the highest possible score: **5.5/5.5** on both projects.

## Team Members

- **Noemi Bongiorni**  
- **Alessandro Pedone**  
- **Simone Licciardi**  
- **Federico Maria Riva**  

---

## Projects

### 1. Blood Cell Classification (Homework 1)
**Objective:**  
Classify blood cells in RGB images into eight disjoint classes using a convolutional neural network (CNN).

**Key Highlights:**
- **Dataset:** 13,759 RGB images (96x96 resolution), filtered to 11,959 images after preprocessing.
- **Methodology:** 
  - Built a baseline CNN architecture with regularization and augmentation.
  - Implemented Transfer Learning (TL) and Fine Tuning (FT) with architectures such as ConvNeXt and EfficientNet.
  - Deployed an ensemble of the best-performing models for improved accuracy and robustness.
- **Final Results:**
  - **Codabench Score:** 0.76
  - **Top Accuracy (ConvNeXtSmall):** 96.20%

Find detailed information in the [HW1 Report](HW1_report_NoPainNoTrain.pdf).

---

### 2. Mars Terrain Segmentation (Homework 2)
**Objective:**  
Segment grayscale Mars terrain images into five classes: Background, Soil, Bedrock, Sand, and Big Rock.

**Key Highlights:**
- **Dataset:** 2,615 grayscale images (64x128 resolution), filtered to 2,505 images.
- **Methodology:**
  - Impemented Keras custom layer for Egde Decetions, Thesholding and others methods of computer vision
  - Explored a dual UNet architecture (Global and Local perspectives).
  - Designed a custom loss function combining Dice Loss, Focal Loss, and Boundary Loss.
  - Applied advanced data augmentation and optimization techniques.
- **Final Results:**
  - **Mean IoU (Kaggle):** 64.91% (Baseline: 32.81%)
- **Kaggle Competition Link:** [AN2DL 2024-2025 Homework 2](https://www.kaggle.com/competitions/an-2-dl-2024-2025-homework-2/discussion?sort=hotness)

Find detailed information in the [HW2 Report](HW2_report_NoPainNoTrain.pdf).

---
