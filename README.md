# Research – fMRI and Amyloid PET Common Factors  
![Python](https://img.shields.io/badge/Python-3.11-blue)
![Neuroimaging](https://img.shields.io/badge/Field-Neuroimaging%20%7C%20AI-purple)
![fMRI](https://img.shields.io/badge/Modality-fMRI-red)
![PET](https://img.shields.io/badge/Modality-Amyloid%20PET-orange)
![Typst](https://img.shields.io/badge/Typeset-Typst-9cf)
![License](https://img.shields.io/badge/License-MIT-yellow)
![Status](https://img.shields.io/badge/Phase-1%20Complete-brightgreen)
### Phase 1: Literature Review & Theoretical Foundation  
**Author:** [Zainab Jamil](https://github.com/zainabjamil-ai)  
**Affiliation:** NCAI Canada  
**Supervisor:** Dr. Ahmad Farooq  
**Date:** November 3, 2025  

---

##  Overview  
<img align="right" alt="Coding" width="300" src="https://media.springernature.com/lw1200/springer-static/image/art%3A10.1007%2Fs13311-021-01030-9/MediaObjects/13311_2021_1030_Fig1_HTML.jpg">

This repository presents the **first phase** of my research project conducted at **NCAI Canada**, focusing on the intersection between **functional MRI (fMRI)** and **Amyloid PET imaging** in **Alzheimer’s Disease (AD)**.  
It explores the **shared functional and structural biomarkers** underlying AD progression, particularly how **neural network disruptions** observed via fMRI relate to **amyloid-beta accumulation** captured by PET imaging.  

---

##  Phase 1 – Literature Review  
This phase establishes the **theoretical foundation** for the project, summarizing key neuroimaging metrics and their relevance to AD pathology.

### 🔹 fMRI Metrics  
- **Functional Connectivity (FC):** Reduced synchrony within the Default Mode Network (DMN), especially the PCC and precuneus.  
- **Amplitude of Low-Frequency Fluctuations (ALFF):** Reflects spontaneous neuronal activity; decreased ALFF in DMN regions indicates hypoactivity.  
- **Regional Homogeneity (ReHo):** Measures local coherence; reduced in hippocampus and posterior cingulate.  
- **Graph Theory Metrics:** Altered degree centrality, global efficiency, and hubness reveal network disintegration patterns.  

### 🔹 Amyloid PET Quantification  
- **SUVr (Standardized Uptake Value Ratio):** Core quantitative biomarker for amyloid burden.
  
  $$
SUV = \frac{\text{radioactive concentration}}{\text{injected activity} / \text{body weight}} 
$$

- **Centiloid Scaling:** Provides a standardized 0–100 scale for cross-study comparison.  
- **Reference-Based Z-Scores:** Normalizes patient values to healthy baselines.  
- **Regional Amyloid Accumulation:** Earliest deposition occurs in DMN hubs, *precuneus, posterior cingulate, medial orbitofrontal cortex.*


  <div align="center">
  <img alt="Coding" width="500" src="https://i.pinimg.com/originals/1b/01/c0/1b01c0eb362f6ac03a66c04d08613271.png" />
</div>

  
---

## 🧬 Linking Both Modalities  
The review highlights converging evidence that:  
> **Amyloid accumulation disrupts functional connectivity within the DMN, while network vulnerability may accelerate amyloid spread.**  

This bidirectional interaction suggests that multimodal imaging (fMRI + PET) can provide **early, non-invasive biomarkers** for Alzheimer’s detection and progression monitoring.  

---

##  Reviewed Research Papers  
- **Graph Convolutional Networks for Amyloid Prediction (2023)** — fMRI-based graph learning predicts PET phenotypes with 78.8% accuracy.  
- **ADNI Cohort Longitudinal Analysis (2025)** — SUVR and shape features predict MCI-to-AD conversion with AUC ≈ 0.9.  
- **PET-MRI Comparative Study (2024)** — Hybrid PET–MRI improves amyloid quantification accuracy.  
- **Deep Learning Assessment of Amyloid, Tau, and Neurodegeneration (2023)** — MRI-based CNNs achieve strong biomarker classification across the AD spectrum.  

---

## 📁 Repository Contents  
```
fMRI-AmyloidPET-Review/
├── NCAI_Task1.pdf             # Full detailed report (Phase 1)        
├── README.md                  # This documentation        
└── References.txt             # DOI and paper links
```
--- 

##  Contact  
Zainab Jamil — AI Engineer in training💗👩‍💻

**Email:** jamilzainab91@gmail.com ✨😊

**GitHub:** github.com/zainabjanice

---
