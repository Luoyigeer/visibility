

# 🌫️ Image-Based Visibility Estimation

> A learning repository for image-based visibility estimation.

---

## 📖 Introduction

This warehouse documents my learning journey in the field of visibility estimation. This work encompasses traditional atmospheric scattering models all the way to deep learning methods.

---
## ✅ Completed
- **Atmospheric scattering model derivation** 
- **Dark Channel Prior implementation** 

---
## 📚 Repository Structure


```text
├── notes/                      # Theoretical foundations
│   ├── atmospheric scattering model.md
│   ├── visibility definition.md
│   ├── dataset survey.md
│   ├── metrics and evaluation.md
│   └── papers summary/         
├── traditional/                # Classical methods
│   ├── dark_channel_prior/     # Dark Channel Prior implementation
│   └── contrast_based/         # Contrast-based visibility metrics
├── deep_learning/              # Deep learning approaches  
│   ├── baseline_cnn/           # Baseline regression model
│   ├── physics_guided/         # Physics-guided neural network
│   ├── dataset_augmentation.py
│   └── dataset_prepare.py
├── datasets/                   
│   └── data symlink.py
├── utils/ 
│   ├── metrics.py               # RMSE、MAE、R2
│   ├── visualize.py             # Visualization tools
│   ├── fog simulation.py        
│   └── depth estimation.py      
│ 
├── README.md                    
└── requirements.txt  
