# X-Ray Image Processing
### A Comprehensive Approach for 2D Detector Data from the KISI–Kurchatov Source

## 📄 Overview

This repository contains the source code developed for the scientific article:

> **“ENHANCEMENT OF THE QUALITY OF X-RAY IMAGES OBTAINED USING A HIGH-RESOLUTION TWO-COORDINATE DETECTOR”**

The results of the development and testing of an integrated approach to improving the quality of X-ray images obtained with a high-resolution X-ray camera based on a scintillation screen and a semiconductor matrix are presented. The approach includes data preprocessing, estimation of the instrumental function of the optical system, application of noise suppression algorithms, and image deblurring. Validation of the proposed approach was performed at the Kurchatov Synchrotron Radiation Source (KISI) by comparing processed experimental images of a test object with simulation results. It has been established that the developed approach enables enhancement of spatial resolution and image detail, thereby expanding the capabilities for micro-object analysis and increasing the information content of the obtained data.


<img width="6173" height="4046" alt="рисунок_5_англ" src="https://github.com/user-attachments/assets/24a9c0d9-1509-4174-a82f-23b46e1bddbb" />


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
