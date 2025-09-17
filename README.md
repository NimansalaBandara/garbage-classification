## 🧠 Multi-Class Garbage Classification Using CNN–Transformer Hybrid

## 🧩 Problem Statement

Manual waste sorting is inefficient, time consuming, and often inaccurate especially in large scale recycling systems. Misclassified garbage can lead to contamination, increased processing costs, and environmental harm.

This project aims to automate the process of garbage classification using deep learning. By training a model to recognize five types of waste from images(metal, glass, paper, trash, cardboard, plastic). we can support smarter recycling workflows and promote sustainable waste management.

![Garbage Classification Example](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR2ivWwlWKowyBWCBAvF4y96u76-y7IYUaYnw&s)

-------------------------------------------------------------------------------------------------------------------------------------------------------------------

This project explores how deep learning can support smarter waste management by classifying garbage images into six categories. Accurate classification helps improve recycling systems and reduce environmental impact.

## 📌 Project Summary

- **Model Type**: CNN-Transformer Hybrid
- **Architecture**: MobileNetV2 + Transformer blocks + Global Average Pooling + Fully Connected Classifier
- **Dataset**: five-class garbage image dataset (metal, glass, paper, trash, cardboard, plastic)
- **Performance**:  
  - Training Accuracy: 99%  
  - Validation Accuracy: 94%  
  - Testing Accuracy: 93%

## 🛠️ Tech Stack

- **Python**
- **PyTorch**, **Torchvision**
- **MobileNetV2** (pretrained)
- **Transformer (MultiheadAttention)**
- **Matplotlib**, **PIL**, **TQDM**
- **Kaggle Notebooks**
