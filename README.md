# 🧠 Deep Neural Network for Image Classification (Cat vs Non-Cat)

This project implements a **Deep Neural Network (DNN)** from scratch using only **NumPy** and other core Python libraries to classify images as **cat** or **non-cat**.  
It demonstrates the fundamentals of deep learning — including forward and backward propagation, vectorization, cost computation, and gradient descent optimization — without using high-level frameworks like TensorFlow or PyTorch.

---


---

## 📦 Dataset Details
- **Dataset:** `catvnoncat.h5` (contains both training and test sets)  
- **Training set:** 209 images  
- **Test set:** 50 images  
- **Image size:** 64 × 64 × 3 (RGB)  
- Data stored in **HDF5** format (`.h5`), loaded using the `h5py` library.

---

## 🧰 Libraries Used
- **Python**
- **NumPy**
- **Matplotlib**
- **SciPy**
- **h5py**
- **PIL (Pillow)**

---

## 🚀 Features
- Implemented a **multi-layer DNN** entirely from scratch.  
- Manual coding of:
  - Parameter initialization  
  - Forward propagation  
  - Cost computation  
  - Backward propagation  
  - Gradient descent optimization  
- Visualized learning curves and test results.  
- Used **external images** (in the `images` folder) for prediction testing.

---

## 📈 Results
- Achieved **~80% test accuracy** after hyperparameter tuning.  
- Explored the effects of network depth, activation functions, and learning rate on performance.  

---

## 🧩 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/YashDawange/Deep-Neural-Network-Cat-Classifier.git

