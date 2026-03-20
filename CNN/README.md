##  Dataset

This project uses the **CIFAKE: Real and AI-Generated Synthetic Images** dataset from Kaggle.

Dataset Link:  
https://www.kaggle.com/datasets/birdy654/cifake-real-and-ai-generated-synthetic-images

---

###  Dataset Description

The CIFAKE dataset is designed to distinguish between **real and AI-generated images** using computer vision techniques.

- **Total Images:** 120,000  
  - 60,000 Real Images  
  - 60,000 Fake (AI-generated) Images  

---

###  Data Source

- **Real Images:**  
  Taken from the CIFAR-10 dataset (real-world images across 10 classes)

- **Fake Images:**  
  Generated using **Stable Diffusion (v1.4)** to mimic CIFAR-10 images  

---

### Dataset Structure

The dataset is divided into two main classes:

dataset/

│

├── REAL/

├── FAKE/

 
---

## 📊 Dataset Loading

The dataset was loaded using Keras `ImageDataGenerator`, which automatically detects classes and organizes images.

###  Dataset Summary

- **Training Data:**  
  - 100,000 images  
  - 2 classes (Real, Fake)

- **Validation/Test Data:**  
  - 20,000 images  
  - 2 classes (Real, Fake)

---

###  Output

Found 100000 images belonging to 2 classes.
Found 20000 images belonging to 2 classes.




---

### 🎯 Purpose of the Dataset

The CIFAKE dataset is designed to address the growing challenge of distinguishing between real and AI-generated images. It supports:

- Binary Image Classification (Real vs Fake)  
- Deepfake Detection  
- Computer Vision Research  
- Digital Forensics Applications  

---

###  Challenges in the Dataset

- **High Visual Similarity:**  
  AI-generated images closely resemble real images  

- **Subtle Feature Differences:**  
  Differences exist at texture and pixel level  

- **Generalization Difficulty:**  
  Model must perform well on unseen data  

- **Risk of Overfitting:**  
  Requires proper regularization techniques  

---

###  Why This Dataset?

- Balanced dataset (equal real & fake images)  
- Widely used benchmark dataset  
- Ideal for CNN-based models  
- Strong real-world applications  

---
