## 🌿 Plant Disease Classification (Deep Learning)

A deep learning–based plant disease diagnosis system built using **PyTorch** and **EfficientNet-B0**, trained on the **PlantVillage dataset (38 classes)**.  
The project includes **Grad-CAM** for visual interpretability and provides label mappings and disease metadata.

---

### 🔍 Key Features

- **EfficientNet-B0** transfer learning  
- **38 plant disease classes**  
- **Grad-CAM** heatmaps for model interpretability  
- Clean label mappings (`label_mapping.json`)  
- Disease metadata structure (`disease_info.json`)  
- Ready-to-use trained model (`best_model.pt`)  


---

### 🧠 Model Overview

- **Framework:** PyTorch  
- **Backbone:** EfficientNet-B0 (pretrained on ImageNet)  

**Training approach:**
- Stage 1 — Train classifier head  
- Stage 2 — Fine-tune full network  

**Evaluation includes:**
- Accuracy  
- F1-score  
- Confusion Matrix  

**Explainability:**  
- Grad-CAM to highlight disease-affected regions  

---

### 📘 Dataset

- **PlantVillage (Kaggle)**  
- **38 classes** across multiple plant species  
- RGB leaf images with uniform backgrounds  

---


