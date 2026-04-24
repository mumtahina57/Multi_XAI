📌 Overview


This project presents a deep learning-based framework for skin cancer classification using dermoscopic images, combined with Explainable AI (XAI) techniques to improve interpretability and trustworthiness.

The system integrates multiple deep learning models and explanation methods, and introduces a Multi-XAI Fusion strategy along with an Explainability Consistency Score (ECS) to evaluate explanation reliability.


├── data/                  # Dataset (not included in repo)
├── preprocessing/         # Image preprocessing scripts
├── models/                # CNN, ResNet50, EfficientNet-B3 training code
├── xai/                   # Grad-CAM, SHAP, LIME implementations
├── fusion/                # Multi-XAI fusion and ECS calculation
├── results/               # Output images and evaluation metrics
├── notebooks/             # Colab / Jupyter notebooks
├── README.md
