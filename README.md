# Microplastic-Detection-in-Soil
This repository contains code for the Microplastic detection in soil using Machine Learning.

# Introduction
Microplastics are plastic particles smaller than 5mm.
**Objective:** Detect microplastics in soil accurately
**Input:** Data from soil samples
**Output:**	
  - 1: Presence of microplastics in the soil sample.
  - 0: Absence of microplastics in the soil sample

# Data Collection
- Soil data are collected from an industrial site in suburban region in Mumbai.
- Fourier-transform infrared (FTIR) spectroscopy is applied on these soil sample to get microplastic types.
- 6 microplastic types were used identified:
  - **PBT (16.67%)**: Polybutylene Terephthalate
  - **PE (16.67%):** Polyethylene
  - **PEPP copolymer (16.67%):** Polyethylene-Polypropylene Copolymer
  - **Polycetylene (16.67%):** A polymer of acetylene (C₂H₂)
  - **Polyester (16.67%):** Polyethylene terephthalate (PET)
  - **PP (16.67%):** Polypropylene

# ML models
Following algorithms were implemented
- Logistic Regression
- Support Vector Machine: Linear and RBF kernels were used
- Random Forest
- Gradient Boosting - LightGB, XGBoost
- Neural Network
  - hidden_layer_sizes: [(5,), (10, 5)],
  - learning_rate: [0.1, 0.5, 0.05, 0.01, 0.001]

# Team Member
Bibek Chand (23M0632)
Satyam Kumar (23D1595)
