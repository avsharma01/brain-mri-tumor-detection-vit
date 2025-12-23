# 🧠 Brain Tumor Detection using Vision Transformer (ViT)

This project implements a **Vision Transformer (ViT)**–based deep learning model
for detecting brain tumors from MRI images. The model is trained to classify
brain MRI scans into tumor and non-tumor (or multi-class tumor categories)
using transformer-based attention mechanisms.

A **Gradio web interface** is integrated inside the Jupyter Notebook to allow
interactive testing of the trained model.

---

## 🚀 Demo (Gradio Interface)
The project includes a **Gradio-based web app** for:
- Uploading brain MRI images
- Running inference using the trained ViT model
- Displaying predicted tumor class

> The Gradio app is launched directly from the Jupyter Notebook.

---
## PPT
- **PPT:** Has been uploaded in this repo for better understanding.
---
## 🧠 Model Architecture
- **Architecture:** Vision Transformer (ViT)
- **Approach:** Transformer-based image classification
- **Input:** Brain MRI images(3 classes are of tumor & 1 class is on no tumor)
- **Output:** Multi-class tumor prediction
- **Framework:** PyTorch / TensorFlow 

---

## 📊 Dataset
- Brain MRI image dataset
- Images are preprocessed and resized before training
- Data augmentation and normalization applied

> Dataset is not included in the repository due to size constraints.

---

## 🧪 Training & Evaluation
- Custom training loop implemented in Jupyter Notebook
- Model evaluated on validation/test data
- Performance metrics such as accuracy and loss monitored

---

## 🛠 Tech Stack
- Python
- Vision Transformer (ViT)
- Deep Learning
- Medical Image Processing
- Gradio (for interactive web interface)
- Jupyter Notebook

---

