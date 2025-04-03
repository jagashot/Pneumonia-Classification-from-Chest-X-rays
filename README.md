# 🏥 Chest X-Ray Classification with Deep Learning  

## 📌 Overview  
This project focuses on classifying chest X-ray images into different health conditions using deep learning.  
The model categorizes images into:  
✅ **Healthy**  
❌ **Pneumonia** (further classified as **bacterial** or **viral**)  

The dataset, sourced from [Kaggle](https://www.kaggle.com/), contains **5,863 chest X-ray images** labeled accordingly.  

---

## 🚀 Project Components  

### 🔹 1. Deep Learning Classification  
- Implemented a **neural network** to classify chest X-ray images as either **healthy** or **diseased**.  
- Developed a second model with **three output categories**: healthy, bacterial pneumonia, and viral pneumonia.  

### 🔹 2. Image Embeddings & KNN Classification  
- Generated **embedding vectors** from the classification model.  
- Utilized **K-Nearest Neighbors (KNN)** to classify new images based on their embeddings.  
- Visualized the distribution of different classes using **t-SNE**.  

### 🔹 3. Transfer Learning with Imbalanced Data  
- Addressed **imbalanced training data** by modifying the training and validation sets.  
- Trained the model on a **smaller dataset** while testing on the full validation set to evaluate generalization.  

### 🔹 4. Anomaly Detection for Unhealthy Cases  
- Implemented **anomaly detection** using only "healthy" images as training data.  
- Detected "unhealthy" cases as outliers based on learned representations.  

---

## 🛠 Getting Started  
For setup instructions and execution guidelines, refer to:  
- 📄 [**README (English)**](./readme_EN.md)  
- 📄 [**README (Hebrew)**](./readme_HE.md)  

---

📌 **Contributors**: [Your Name]  
📌 **License**: MIT (if applicable)  
📌 **Dataset**: [Kaggle Dataset](https://www.kaggle.com/)  

Feel free to contribute or raise issues! 🚀  
