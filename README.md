# 🍑 Peach Leaf Disease Classification using Vision Transformer (ViT)

## 📌 Project Overview

This project uses a Vision Transformer (ViT) model to classify peach leaf diseases from images. The model is trained using PyTorch and the TIMM library for image classification.

The goal is to automatically identify whether a peach leaf is healthy or diseased, helping farmers and agricultural experts detect plant diseases early.

---

## 🚀 Features

- Image Classification using Vision Transformer (ViT)
- PyTorch-based implementation
- Data preprocessing and augmentation
- Model training and evaluation
- Confusion Matrix visualization
- Classification Report
- Accuracy and Loss Curves

---

## 📂 Dataset

Dataset Structure:

```
dataset/
│
├── Healthy/
│   ├── image1.jpg
│   ├── image2.jpg
│
└── Diseased/
    ├── image1.jpg
    ├── image2.jpg
```

Classes:

- Healthy
- Diseased

---

## 🛠 Technologies Used

- Python
- PyTorch
- TorchVision
- TIMM
- NumPy
- Matplotlib
- Scikit-Learn
- Seaborn

---

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/peach-leaf-disease-classification.git
cd peach-leaf-disease-classification
```

Install dependencies:

```bash
pip install torch torchvision timm numpy matplotlib scikit-learn seaborn
```

---

## ▶️ Running the Project

Open the notebook:

```bash
jupyter notebook peach-leaf-disease-classification.ipynb
```

Run all cells sequentially.

---

## 🧠 Model Architecture

This project uses:

- Vision Transformer (ViT Tiny)
- Patch Size: 16 × 16
- Input Image Size: 224 × 224
- Output Classes: 2

---

## 🔄 Workflow

1. Load Dataset
2. Preprocess Images
3. Split Dataset
4. Create DataLoaders
5. Initialize ViT Model
6. Train Model
7. Evaluate Performance
8. Generate Confusion Matrix
9. Generate Classification Report

---

## 📊 Evaluation Metrics

The model is evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

---

## 📈 Training Visualization

The notebook includes:

- Training Loss Curve
- Validation Loss Curve
- Accuracy Curve

---


### Confusion Matrix

![Confusion Matrix](images/confusion_matrix.png)

### Training Curves

![Training Curve](images/training_curve.png)

---

## 🔮 Future Improvements

- Use larger datasets
- Apply data augmentation
- Hyperparameter tuning
- Deploy using Streamlit
- Convert model to API
- Multi-class disease classification

---

## 👨‍💻 Author

Sohail Ahmad

GitHub: https://github.com/sohail-ahmad-ux

---

## 📜 License

This project is licensed under the SmartLab ICP License.
