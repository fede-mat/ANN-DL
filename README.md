<!-- omit form toc -->
# Blood Cells Recognition: an Image Recognition task

Project for the _Artificial Neural Networks and Deep Learning_ course held at Politecnico di Milano in the academic year 2024-2025 by Professor Boracchi and Professor Matteucci.

> 🏆 This project received a perfect evaluation of 5.5/5.5. 

<!-- omit from toc -->
# Table of contents

- [Installing](#installing)
  - [Prerequisites](#prerequisites)
  - [Cloning the Repository](#cloning-the-repository)
  - [Installing the Libraries](#installing-the-libraries)
- [Project](#project)
- [Results](#results)
- [Structure](#structure)
- [Authors](#authors)

# Installing

## Prerequisites

- Python 3.x
- Pip (for installing Python libraries)

## Cloning the Repository

1. Clone the repository to your local machine using the following command:
```bash
git clone https://github.com/fede-mat/an2dl
```

2. Navigate to the project directory using the following command:
```bash
cd an2dl
```

## Installing the Libraries

With Pip, install the required libraries by running the following command:
```bash
pip install -r requirements.txt
```

# Project

**Objective:** perform an 8-class classification task on blood cells images.

**Dataset:** 13,759 RGB images (96x96 resolution), filtered to 11,959 images after preprocessing.

**Methodology:** 
  - Built an initial CNN architecture with regularization and augmentation as benchmark.
  - Implemented Transfer Learning (TL) and Fine Tuning (FT).
  - Deployed an ensemble of the best-performing models.

# Structure

The repository [`source`](./source/) contains four notebooks, to train the models and generate their ensemble: namely, [`model1`](./source/model1.ipynb), [`model2`](./source/model2.ipynb), [`model3`](./source/model3.ipynb), and [`ensemble`](./source/ensemble.ipynb).

The repository [`archive`](./archive/) is an history of our trials and its elements are detailed in the report.

# Results

Our model achieved a 76% test set accuracy and perfect evaluation.
You can check out the final [`report.pdf`](./report/report.pdf). 

# Authors

- Noemi Bongiorni ([@NoemiBongiorni](https://github.com/NoemiBongiorni))
- Simone Licciardi ([@simone-licciardi](https://github.com/simone-licciardi))
- Alessandro Pedone ([@alessandropedone](https://github.com/alessandropedone))
- Federico Maria Riva ([@fede-mat](https://https://github.com/fede-mat))



<!-- 
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

--- -->
