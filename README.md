# ViTGNN

**ViT-GNN model for SARS-CoV-2 detection**

ViTGNN is a hybrid deep learning framework that combines **Vision Transformers (ViT)** and **Graph Neural Networks (GNN)** for the classification of SARS-CoV-2 from CT scans. The model leverages CNN-based feature extraction, GNN-based spatial reasoning, and ViT-based global context to deliver robust medical imaging performance.

---

## Features

- Hybrid CNN-GNN-ViT architecture
- COVID-19 vs. Non-COVID CT scan classification
- PyTorch Lightning-based modular training pipeline
- Multi-stage training: CNN ➝ CNN+GNN ➝ ViT classifier
- Custom configuration and reproducible experiments

---

## Model Architecture

1. **CNN Backbone** – Extracts low-level visual features from CT scans  
2. **Graph Neural Network (GNN)** – Builds a patch-level spatial graph and learns inter-regional relationships  
3. **Vision Transformer (ViT)** – Captures global contextual information and performs final classification  

---



