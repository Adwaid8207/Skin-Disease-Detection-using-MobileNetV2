# 🩺 Skin Disease Detection with MobileNetV2

A beginner deep learning project that uses **MobileNetV2** for classifying 8 types of skin diseases from images. Built using **TensorFlow** and trained in **Google Colab**.

---

## 🔧 Tools Used
- TensorFlow / Keras
- MobileNetV2 (feature extraction)
- Google Colab
- Kaggle dataset

---

## 📂 Dataset
[Kaggle - Skin Disease Dataset](https://www.kaggle.com/datasets/subirbiswas19/skin-disease-dataset)

---

## 📦 Trained Model
Due to size limits, the model is stored on Google Drive:  
[👉 Download skin_disease_model.h5](https://drive.google.com/drive/folders/1Tss2M166Ni8RgDO4fho6xj-XWNBggXv1)

To use it:
```python
from tensorflow.keras.models import load_model
model = load_model("skin_disease_model.h5")
