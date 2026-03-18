# DeepLense GSoC 2026: Solutions for Strong Lensing Analysis

Hi! I'm Dundi Kuladeepeswar, a B.Tech student from IIT Patna specializing in AI & Data Science. This repository contains my technical solutions for the GSoC 2026 DeepLense project, focusing on **Super-Resolution**, **Foundation Models (MAE)**, and **Domain Adaptation**.

## 🚀 Key Achievements

* **Super-Resolution (Task VI.A):** Achieved an elite **42.13dB PSNR** and **0.9774 SSIM** using a Transformer-based SwinIR architecture.
* **Foundation Models (Task IX.A):** Successfully implemented a **Masked Autoencoder (MAE)** on simulated lensing data, reaching a Multi-class **AUC of 0.9966**.
* **Real-World Adaptation (Task VI.B):** Bridged the simulation-to-real gap using few-shot learning on HST/HSC telescope data, maintaining structural integrity with a **0.8065 SSIM**.

---

## 📁 Project Overview

### 🌌 Common Test: Multi-Lens Classification
Implementation of a robust ensemble approach for initial lens screening.
* **Final AUC:** 0.9845

### 🔭 Task VI: Super-Resolution (SR)
Focused on restoring low-resolution simulated and real-world astronomical images.
* **Technical Highlights:** SwinIR architecture, hybrid Edge-MSE loss functions, and few-shot fine-tuning for limited real datasets (300 pairs).

### 🤖 Task IX: Foundation Models
Development of a Vision Transformer (ViT) backbone trained via Self-Supervised Learning.
* **Technical Highlights:** Random masking (75%), Sin-Cos positional embeddings, and downstream classification for CDM and Axion substructures.

---

## 🛠️ Tech Stack
* **Frameworks:** PyTorch, Torch.amp, Timm
* **Libraries:** NumPy, Scikit-learn, Matplotlib, Einops
* **Hardware:** Trained using Dual NVIDIA T4 GPUs on Kaggle

---

## 📬 Contact
If you have any questions about my implementation or results, feel free to reach out!
* **Email:** dundikuladeepeswar@gmail.com
