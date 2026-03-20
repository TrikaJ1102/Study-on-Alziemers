# 🧠 Alzheimer’s Disease Classification using MRI (Deep Learning)

## 📌 Objective

To develop a deep learning-based system for classifying brain MRI images into different stages of Alzheimer’s disease using:

* Data Preprocessing
* Data Augmentation
* Exploratory Data Analysis (EDA)
* Stratified K-Fold Cross Validation

---

## 🧠 Problem Statement

Alzheimer’s disease is a progressive neurodegenerative disorder that causes memory loss and cognitive decline.

Early detection is crucial for effective treatment and patient care.

This project aims to classify MRI brain images into four categories:

* Non-Demented
* Very Mild Demented
* Mild Demented
* Moderate Demented

using preprocessing techniques and data analysis to prepare the dataset for model training.

---

## 📂 Dataset Description

The dataset consists of MRI brain scans organized into folders:

```
Alzheimer_s Dataset/
│
├── train/
│   ├── NonDemented/
│   ├── VeryMildDemented/
│   ├── MildDemented/
│   └── ModerateDemented/
│
└── test/
```

* Images are grayscale MRI scans
* Dataset shows **class imbalance** (Non-Demented has more samples)

---

## ⚙️ Methodology

### 🔹 1. Data Preprocessing

* Resizing images to **224 × 224**
* Normalizing pixel values (0–1 scaling)
* Converting images to grayscale format

---

### 🔹 2. Data Augmentation

Applied to improve model generalization:

* Rotation
* Zoom
* Horizontal Flip
* Width & Height Shift

---

### 🔹 3. Data Generators

Used `ImageDataGenerator` for:

* Efficient loading of images
* Real-time preprocessing
* Training, validation, and testing splits

---

### 🔹 4. Stratified K-Fold Cross Validation

* Ensures balanced class distribution in each fold
* Improves reliability of evaluation
* Reduces bias compared to single split

---

### 🔹 5. Exploratory Data Analysis (EDA)

* Visualized sample MRI images
* Compared original vs augmented images
* Analyzed class distribution using:

  * Bar Graph
  * Pie Chart

---

## 🧠 Key Concepts Used

* ✅ Deep Learning (CNN Preparation)
* ✅ Image Processing
* ✅ Data Augmentation
* ✅ Stratified Sampling
* ✅ Model Evaluation Techniques
* ✅ Data Visualization

---

## 📊 Observations

* Dataset is **imbalanced**
* Augmentation helps improve minority class representation
* Normalization improves training stability
* Stratified K-Fold provides **more reliable results**

---

## 🚀 Conclusion

This project successfully prepares MRI image data for Alzheimer’s disease classification using preprocessing, augmentation, and analysis techniques.

The dataset is now well-structured and ready for training deep learning models like CNNs (e.g., ResNet-18).

---

## 📁 Files Included

* `DPEL Project.ipynb` (or `.py`)
* Dataset (Alzheimer MRI Dataset)

---

## 🔮 Future Scope

* Implement CNN models (ResNet, VGG, etc.)
* Improve accuracy using transfer learning
* Deploy model as a web or mobile application
* Integrate explainability (XAI) for medical insights

---

👨‍💻 Author

Trika Jaiswal
BTech AI & ML Student
