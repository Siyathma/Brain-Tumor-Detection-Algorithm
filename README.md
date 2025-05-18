# 🧠 Brain Tumor Detection with CNN

This project uses Convolutional Neural Networks (CNNs) to classify brain MRI images into four categories:  
- **Glioma Tumor**  
- **Meningioma Tumor**  
- **Pituitary Tumor**  
- **No Tumor**

Advanced data augmentation techniques such as **CutMix** and **MixUp** were used to improve model performance and generalization.

---

## 📂 Dataset

The dataset contains MRI images organized into `Training` and `Testing` folders. We further split the training set to create a validation set.

- Image size standardized to **244×244**  
- Total:  
  - Training images: **2870**  
  - Testing images: **394**

---

## ⚙️ Preprocessing Steps

1. Installed required libraries and loaded dataset  
2. Standardized image size and labels  
3. Split training data into training and validation sets  
4. Converted images to NumPy arrays for model input  
5. Applied CutMix and MixUp for augmentation  

---

## 🧠 Model

- Built using **Convolutional Neural Networks**
- Trained on preprocessed MRI images
- Optimized using augmented data

---

## 📈 Results

- Achieved high accuracy on test data  
- Model can effectively classify the type of brain tumor from MRI images

---

## 🚀 How to Run

1. Clone the repository  
2. Install dependencies  
   ```bash
   pip install -r requirements.txt
