# 🌾 Rice Variety Classification using EfficientNet–ViT Fusion

## 📌 Overview

This project presents a deep learning-based approach for **rice variety classification** using a hybrid model that combines **EfficientNet** and **Vision Transformer (ViT)** architectures. The model leverages both convolutional feature extraction and transformer-based global attention for improved performance.

---

## 🎯 Objectives

* Classify rice images into multiple varieties
* Improve accuracy using hybrid deep learning architecture
* Provide a reproducible and scalable pipeline

---

## 🧠 Model Architecture

* EfficientNet (feature extraction)
* Vision Transformer (global representation)
* Fusion layer combining both outputs
* Final classification layer

---

## 📊 Classes

The model classifies rice into the following categories:

* Arborio
* Basmati
* Ipsala
* Jasmine
* Karacadag

---

## 📦 Dataset

The dataset used in this project is sourced from Kaggle:

👉 **Rice Image Dataset**
🔗 https://www.kaggle.com/datasets/muratkokludataset/rice-image-dataset

Due to GitHub size limitations, the dataset is **not included in this repository**.

### 🔽 Download using Python

```python
import kagglehub

path = kagglehub.dataset_download("muratkokludataset/rice-image-dataset")
print("Path to dataset files:", path)
```

---

## 📁 Project Structure

```
RICE-VIT-FUSION/
│── data/                  # (ignored - dataset not uploaded)
│── unzipped_dataset/      # (ignored - raw images)
│── models/                # (ignored - model weights)
│── results/               # output results and plots
│
│── Rice_EfficientNet_ViT_Fusion.ipynb
│── README.md
│── .gitignore
```

---

## ⚙️ Installation

```bash
pip install -r requirements.txt
```

---

## 🚀 Usage

1. Download the dataset using KaggleHub
2. Place dataset in appropriate directory (`data/` or `unzipped_dataset/`)
3. Run the notebook:

```bash
jupyter notebook
```

4. Open:

```
Rice_EfficientNet_ViT_Fusion.ipynb
```

---

## 🧪 Results

The project includes:

* Confusion matrices
* Accuracy comparison plots
* Classification reports

All results are available in the `results/` folder.

---

## ⚠️ Notes

* Large files such as datasets and trained models are excluded from this repository.
* Ensure proper file paths when running the notebook.
* GPU is recommended for faster training.

---

## 🔮 Future Work

* Deploy as a web application
* Optimize model for real-time inference
* Extend to more crop types
