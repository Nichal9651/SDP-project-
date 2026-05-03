SDP PROJECT
 Fine-Grained Bird Species Classification
 Overview

This project focuses on fine-grained bird species classification using a Swin Transformer with Part-Based Attention Mechanism. The model is designed to capture both global and local discriminative features for accurate classification of visually similar bird species.

 Results
 Top-1 Accuracy: 90.33%
 Stable training convergence
 Grad-CAM shows focus on bird parts
 Methodology
Swin Transformer (global features)
Part-Based Attention (local features)
Feature Fusion
Test-Time Augmentation (TTA)
📂 Dataset
CUB-200-2011 Dataset
200 bird species
11,788 images
⚙️ Installation
pip install -r requirements.txt
▶️ Run Training
final(1) all.pynb
📸 Results

Including all there in my notebook:

Accuracy graph
Confusion matrix
Grad-CAM images
🔮 Future Work
Object Detection + Classification pipeline
Real-time bird recognition
Lightweight deployment
📌 Author

Nichal Haas

📦 requirements.txt
torch
torchvision
timm
numpy
pandas
matplotlib
seaborn
scikit-learn
opencv-python
