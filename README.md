# Chair of Informatics for Medical Technologies (CIMT)  
### University of Augsburg

[![Website](https://img.shields.io/website?label=Website&url=https%3A%2F%2Fcimt-university-of-augsburg.github.io&style=flat&logo=github)](https://cimt-university-of-augsburg.github.io)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

This repository hosts the official **public website** for the **Chair of Informatics for Medical Technologies (CIMT)** at the [University of Augsburg](https://www.uni-augsburg.de).

The site showcases our research vision, core work areas, technical infrastructure, and open-source neurotechnology tools.

---

## 🔬 Research Focus

We develop **innovative systems and procedures for diagnostics and medical monitoring**, with an emphasis on:
- **Biomechanical & electrophysiological movement analysis**
- **Electrophysiological analysis of brain activity** (EEG/MEG)
- **Sensor development**, signal processing, and AI-driven interpretation
- Applications in **neurology, cardiology, sports science, and human-computer interaction**

Our approach is **user-centered, reproducible, and grounded in open science**.

---

## End-to-End EEG Analysis Pipeline

We provide a fully automated, modular pipeline for high-density (280-channel) EGI EEG data via **Hugging Face Spaces**:

| Stage | App | Function |
|------|-----|--------|
| **1. Preprocessing** | [**ICA_Xtra**](https://huggingface.co/spaces/CIMT/ICA_Xtra) | Bad channel detection, ICA-based artifact removal, filtering |
| **2. Source Estimation** | [**LCMV_Xtra**](https://huggingface.co/spaces/CIMT/LCMV_Xtra) | LCMV beamformer on fsaverage, DiFuMo time series extraction |
| **3. Functional Connectivity** | [**FC_Xtra**](https://huggingface.co/spaces/CIMT/FC_Xtra) | Debiased WPLI connectivity across 87 cognitive/motor regions |

✅ **No manual intervention required**  
✅ **Reproducible, standardized, and zero-config**  
✅ Designed for **batch processing** and **non-expert users**
