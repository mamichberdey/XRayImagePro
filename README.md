# X-Ray Image Processing
### A Comprehensive Approach for 2D Detector Data from the KISI–Kurchatov Source

<img width="5949" height="3925" alt="рисунок_5_англ" src="https://github.com/user-attachments/assets/eb007324-e887-4354-a3c7-f122a22807c5" />


## 📄 Overview

This repository contains the source code developed for the scientific article:

> **“ENHANCEMENT OF THE QUALITY OF X-RAY IMAGES OBTAINED USING A HIGH-RESOLUTION TWO-COORDINATE DETECTOR”**

The work presents the development and experimental validation of an integrated methodology aimed at improving the quality of X-ray images acquired using a two-dimensional detector at the **KISI–Kurchatov** radiation source. The primary objective is to achieve **optimal spatial resolution** while preserving physically meaningful image details.

## 🎯 Objectives

- Improve spatial resolution of X-ray images  
- Reduce noise and instrumental artifacts  
- Compensate for optical system blurring  
- Provide a reproducible and modular processing pipeline for scientific use  

## 🧠 Methodology

The proposed approach is based on a **multi-stage image processing pipeline**, which includes:

1. **Preprocessing of Raw Data**
   - Detector calibration
   - Background correction
   - Intensity normalization

2. **Precise Estimation of the Instrumental Response**
   - Evaluation of the optical system’s instrumental (MTF) function
   - Characterization of system-induced blurring

3. **Noise Suppression**
   - Application of noise reduction algorithms
   - Preservation of fine structural details

4. **Deblurring and Image Restoration**
   - Compensation for optical distortions
   - Restoration techniques based on the estimated instrumental function

Each stage is designed to be independently configurable and reproducible.

## 🧪 Experimental Validation

The algorithms were tested on experimental data obtained at the **KISI–Kurchatov** facility. The results demonstrate a significant improvement in image clarity and spatial resolution compared to raw detector data.
