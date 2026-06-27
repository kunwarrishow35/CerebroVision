# 🧠 CerebroVision

> **Brain Tumor Classification using Deep Learning & Explainable AI**

![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python&logoColor=white)

![TensorFlow](https://img.shields.io/badge/TensorFlow-2.20-FF6F00?logo=tensorflow&logoColor=white)

![OpenCV](https://img.shields.io/badge/OpenCV-4.10-5C3EE8?logo=opencv&logoColor=white)

![NumPy](https://img.shields.io/badge/NumPy-1.26-013243?logo=numpy&logoColor=white)

![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-1.5-F7931E?logo=scikitlearn&logoColor=white)

![Deep Learning](https://img.shields.io/badge/Deep-Learning-red)

![Transfer Learning](https://img.shields.io/badge/Transfer-Learning-success)

![Grad--CAM](https://img.shields.io/badge/Explainability-Grad--CAM-blueviolet)

![ResNet50](https://img.shields.io/badge/Model-ResNet50-success)
---

## 📌 Overview

CerebroVision is a deep learning project that classifies **brain MRI scans** into four categories using **ResNet50 Transfer Learning**. The project also integrates **Grad-CAM (Gradient-weighted Class Activation Mapping)** to provide visual explanations of the model's predictions, making the decision-making process more transparent and interpretable.

---

## ✨ Features

* 🧠 Multi-class Brain Tumor Classification
* 🚀 Transfer Learning using ResNet50
* 🔧 Fine-Tuning of the pre-trained model
* 📊 Training & Validation Performance Analysis
* 📈 Confusion Matrix & Classification Report
* 🔥 Explainable AI using Grad-CAM
* 💾 Best Model Saving for Deployment
* 📂 Organized Training Pipeline

---

## 🩺 Tumor Classes

The model classifies MRI scans into the following four classes:

* Glioma
* Meningioma
* No Tumor
* Pituitary Tumor

---

## 🏗️ Model Architecture

The classification model is built using:

* **ResNet50** (ImageNet Pre-trained)
* Global Average Pooling Layer
* Dense Layer (256 units, ReLU)
* Dropout Layer (0.5)
* Dense Output Layer (Softmax - 4 Classes)

---

## ⚙️ Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* OpenCV
* Matplotlib
* Scikit-learn
* tf-keras-vis
* Google Colab

---

## 📊 Model Performance

| Metric            |     Result |
| ----------------- | ---------: |
| Test Accuracy     | **95.19%** |
| Base Model        |   ResNet50 |
| Number of Classes |          4 |
| Explainability    |   Grad-CAM |

---

## 🔥 Explainable AI

To improve interpretability, Grad-CAM is used to generate heatmaps highlighting the regions of the MRI scan that contributed most to the model's prediction.

This enables users to better understand how the deep learning model reaches its decisions.

---

## 📂 Project Structure

```text
CerebroVision/
│
├── CerebroVision_Training.ipynb
├── README.md
├── requirements.txt
├── .gitignore
│
├── models/
│   └── best_model.keras
│
├── data/
│
└── images/
```

---

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/CerebroVision.git
```

Move into the project directory:

```bash
cd CerebroVision
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ Usage

1. Open the notebook `CerebroVision_Training.ipynb`.
2. Load the MRI dataset.
3. Train the model or load the provided trained model.
4. Evaluate the model.
5. Generate Grad-CAM visualizations.

---

## 📈 Results

The fine-tuned ResNet50 model achieved:

* ✅ **95.19% Test Accuracy**
* ✅ Strong performance across all four MRI classes
* ✅ Explainable predictions using Grad-CAM
* ✅ Robust transfer learning through fine-tuning

---

## 🔮 Future Improvements

* Streamlit Web Application
* Cloud Deployment
* PDF Prediction Reports
* Additional Explainable AI Methods (LIME / SHAP)
* Support for More MRI Datasets

---

## 👨‍💻 Author

**Rishow Kunwar**

B.Tech CSE (AI & ML)

Institute of Engineering & Management (IEM), Kolkata

---

## ⭐ Support

If you found this project interesting, consider giving the repository a ⭐ on GitHub.
