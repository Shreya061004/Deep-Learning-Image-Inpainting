# Deep Learning Image Inpainting

A deep learning project focused on **image inpainting and reconstruction of images with missing or irregular regions**.

This project was developed as part of my work during an internship in the field of computer vision and deep learning.

## Overview

Image inpainting is the process of reconstructing missing or damaged regions of an image while maintaining visual consistency with the surrounding content.

The project explores a deep learning-based approach for image reconstruction and evaluates the quality of the generated images using quantitative and visual analysis.

## Project Components

### 1. Image Inpainting

The main notebook focuses on developing and experimenting with a deep learning-based image inpainting pipeline.

It includes:

* Image dataset preparation
* Creation of missing/irregular regions using masks
* Deep learning-based image reconstruction
* Model training and evaluation
* Visualization of masked and reconstructed images

**Notebook:** `main-image-inpainting.ipynb`

### 2. Resolution and Image Quality Analysis

The second notebook investigates the effect of different image resolutions on the inpainting process.

The reconstructed images are evaluated using:

* **PSNR (Peak Signal-to-Noise Ratio)**
* **SSIM (Structural Similarity Index)**

The experiments provide both quantitative metrics and visual comparisons of the reconstructed images.

**Notebook:** `resolution-and-metrics-analysis.ipynb`

## Evaluation

The quality of the reconstructed images is assessed using PSNR and SSIM.

* **PSNR** measures the similarity between the original and reconstructed images based on pixel-level differences.
* **SSIM** evaluates structural similarity between the original and reconstructed images.

These metrics are used alongside visual inspection to analyze reconstruction quality.

## Repository Structure

```text
Deep-Learning-Image-Inpainting/
│
├── README.md
│
└── notebooks/
    ├── main-image-inpainting.ipynb
    └── resolution-and-metrics-analysis.ipynb
```

## Technologies Used

* Python
* Jupyter Notebook
* Deep Learning
* Computer Vision
* TensorFlow / Keras
* NumPy
* OpenCV
* Matplotlib
* Scikit-image

## Key Areas

* Image Inpainting
* Deep Learning
* Image Reconstruction
* Computer Vision
* Image Quality Assessment
* PSNR and SSIM
* Resolution-based Analysis

## Internship Context

This project represents work carried out during my internship in the area of **computer vision and deep learning**.

The repository contains selected experiments and implementations from the project, organized for reproducibility and portfolio presentation.

## Note

The datasets used in the experiments are not included in this repository. Dataset paths and setup may need to be modified according to the local environment.
