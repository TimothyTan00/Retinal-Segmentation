# Automated Retinal Layer Segmentation for Disease Diagnosis

## 📌 Overview
This project focuses on developing an automated segmentation algorithm for retinal OCT (Optical Coherence Tomography) images. By refining boundary detection methods and integrating segmentation outputs with deep learning models, we aim to improve the precision of classifying retinal diseases such as Age-Related Macular Degeneration (AMD), Choroidal Neovascularization (CNV), Diabetic Macular Edema (DME), Central Serous Retinopathy (CSR), Macular Hole (MH), Diabetic Retinopathy (DR), Diabetic Macular Edema (DME), and Drusen.

## 🔹 Key Features
* **Automated Retinal Layer Segmentation**: Uses advanced image processing techniques to delineate key retinal boundaries.
* **Computer Vision Techniques**: Implements peak detection, path extension algorithms, and intensity-based analysis to refine layer detection.
* **Deep Learning Integration**: Enhances pre-trained models by providing high-accuracy segmentation masks for disease classification.
* **Scalable & Generalizable**: Designed to work with multiple retinal disease datasets for broader diagnostic applications.

! [Retinal Segmentation Example]
(https://github.com/TimothyTan00/Retinal-Segmentation/blob/main/NEW%20FINAL%20IMAGE%20202.png?raw=true)

## 🛠 Methodology
1. **Preprocessing**: Image normalization, denoising, and gradient-based transformations.
2. **Layer Segmentation**: Detects and delineates key retinal boundaries using peak detection and path optimization.
3. **Validation**: Compares segmentation outputs with expert-labeled ground truths to ensure accuracy.
4. **Integration with Deep Learning**: Segmentation outputs are used to refine classification models for disease prediction.

## 📊 Dataset
This project uses publicly available OCT datasets labeled for retinal diseases. You can find relevant datasets from:
* [OCT2017 Dataset](https://www.kaggle.com/datasets/paultimothymooney/kermany2018)
* [OPENICPSR Dataset](https://www.openicpsr.org/openicpsr/project/108503/version/V1/view)
* [OCTID Dataset](https://www.kaggle.com/datasets/kawtarnaim/octid-dataset)

## 📝 Repository Notice
The core implementation and source code are currently private due to ongoing research and intellectual property considerations.
