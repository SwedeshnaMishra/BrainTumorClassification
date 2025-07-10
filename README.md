# 🧠 Brain Tumor Classification 

An AI-powered system that automates the classification of brain tumors using MRI scans to enhance diagnostic accuracy and reduce human error.

---

## 📌 Objective

Effective treatment and patient survival depend on the **early and precise detection** of brain tumors. Traditional manual MRI diagnosis is often time-consuming and prone to inaccuracies. This project leverages deep learning to:

- 🧪 **Automate MRI Analysis**: Reduce human error through reliable AI predictions.
- 🚀 **Enable Early Detection**: Classify tumors faster to facilitate timely treatment.
- 💡 **Support Decision-Making**: Classify tumor types (glioma, meningioma, pituitary) to assist medical professionals.

This solution aims to bridge the gap between **AI-driven diagnostics** and traditional radiological evaluation, enhancing patient care and treatment success.

---

## 🛠️ Methodology

Followed a systematic deep learning pipeline:

### 📁 Dataset
- Public MRI dataset from Kaggle:  
  [Brain Tumor Classification (MRI)](https://www.kaggle.com/datasets/sartajbhuvaji/brain-tumor-classification-mri)

### 🔄 Preprocessing
- Image resizing
- Data augmentation
- Normalization

### 🧠 Model Architecture
- Used CNN-based models like:
  - VGG16
  - ResNet
  - Custom CNN

### ⚙️ Training
- **Optimizer**: Adam  
- **Loss Function**: Categorical Cross-Entropy  
- **Batch Size**: (configured based on hardware)  
- **Epochs**: (tuned through experimentation)

### 📊 Evaluation Metrics
- **Accuracy**: 0.780  
- **Precision**: 0.766  
- **Recall**: 0.800  
- **F1-score**: 0.783  

---

## ✅ Results

The model achieved an accuracy of **78%**, successfully avoiding overfitting while reliably classifying tumors into:
- **Glioma**
- **Meningioma**
- **Pituitary**

These results confirm that the system performs well across key evaluation metrics, showing promise for real-world use in clinical diagnostics.

---

## For Contributing
If you want to contribute to this project, please follow these steps:
- `Fork` the repository.
- Create a new branch `(git checkout -b feature/your-feature-name)`.
- Make your changes and commit them `(git commit -m 'Add some feature')`.
- Push to the branch `(git push origin feature/your-feature-name)`.
- Open a pull request.

---

## Project Maintainer
**Github:** [Swedeshna Mishra](https://github.com/SwedeshnaMishra)
