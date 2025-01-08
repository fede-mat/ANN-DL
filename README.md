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
git clone https://github.com/fede-mat/anndl-hw1
```

2. Navigate to the project directory using the following command:
```bash
cd anndl-hw1
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

The folder [`source`](./source/) contains five notebooks, to investigate the dataset, train the models and generate their ensemble: namely, [`investigate.ipynb`](./source/investigate.ipynb), [`model1.ipynb`](./source/model1.ipynb), [`model2.ipynb`](./source/model2.ipynb), [`model3.ipynb`](./source/model3.ipynb), and [`ensemble.ipynb`](./source/ensemble.ipynb).

The folder [`archive`](./archive/) is an history of our trials and its elements are detailed in the report.

# Results

Our model achieved a 76% test set accuracy and perfect evaluation.
You can check out the final [`report.pdf`](./report/report.pdf). 

# Authors

- Noemi Bongiorni ([@NoemiBongiorni](https://github.com/NoemiBongiorni))
- Simone Licciardi ([@simone-licciardi](https://github.com/simone-licciardi))
- Alessandro Pedone ([@alessandropedone](https://github.com/alessandropedone))
- Federico Maria Riva ([@fede-mat](https://github.com/fede-mat))