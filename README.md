# Handwritten Character Recognition using CNN

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)

## 📌 Project Overview
This project is part of the **CodeAlpha Machine Learning Internship — Task 3**.
It implements a Convolutional Neural Network (CNN) to recognize handwritten digits
using the MNIST dataset with 99%+ accuracy.

## 🗂 Dataset
- **Name:** MNIST
- **Size:** 70,000 images (60,000 train + 10,000 test)
- **Classes:** 10 (digits 0–9)
- **Image Size:** 28×28 pixels (grayscale)

## 🧠 Model Architecture
| Layer | Details |
|-------|---------|
| Conv2D Block 1 | 32 filters, 3×3, ReLU + BatchNorm + MaxPool + Dropout |
| Conv2D Block 2 | 64 filters, 3×3, ReLU + BatchNorm + MaxPool + Dropout |
| Conv2D Block 3 | 128 filters, 3×3, ReLU + BatchNorm + Dropout |
| Dense | 256 units, ReLU + Dropout |
| Output | 10 units, Softmax |

## 📊 Results
- **Test Accuracy:** ~99%
- Metrics: Precision, Recall, F1-Score (per digit class)

## 📁 Project Structure
## ⚙️ Installation & Usage
```bash
# Install dependencies
pip install tensorflow scikit-learn matplotlib seaborn numpy

# Run the script
python codealpha_handwrittencharacterrecognition.py
```

## 📈 Output Files
- `training_history.png` — Accuracy & Loss graphs
- `confusion_matrix.png` — Confusion Matrix heatmap
- `sample_predictions.png` — Sample predictions visualization
- `model/cnn_mnist_model.h5` — Saved trained model

## 🙋 Author
**Kishore Reddy Gayam**
- 🎓 B.Tech CSE (AI/ML) — Marwadi University
- 💼 ML Intern @ CodeAlpha
- 🔗 [LinkedIn](https://linkedin.com/in/kishore-reddy-gayam-867254316)
- 🐙 [GitHub](https://github.com/kishorereddycse860-hub)
