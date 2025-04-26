# 🚀 CIFAR-10 Image Classification with Improved CNN and Transfer Learning Evaluation

This project trains an **improved Convolutional Neural Network (CNN)** on the **CIFAR-10 dataset**, uses **data augmentation** and **regularization techniques**, and evaluates performance using a **confusion matrix** and **accuracy curves**.

---

## 📚 Project Overview

- ✅ Load and preprocess the CIFAR-10 dataset
- 🧹 Normalize images and apply one-hot encoding to labels
- ✨ Enhance data with **image augmentation** (rotation, shifts, flips)
- 🧠 Build a deep CNN with dropout, batch normalization, and L2 regularization
- 📉 Train the model with **learning rate scheduling** for better convergence
- 📈 Evaluate model accuracy and plot confusion matrix
- 🔄 Compare results against a Transfer Learning model

---

## 🛠️ Tech Stack

| Component                 | Tool/Library       |
|----------------------------|--------------------|
| Deep Learning Framework    | `TensorFlow/Keras`  |
| Data Augmentation          | `ImageDataGenerator` |
| Visualization              | `matplotlib`, `seaborn` |
| Evaluation Metrics         | `scikit-learn` (Confusion Matrix) |
| Dataset                    | CIFAR-10            |
| Environment                | Google Colab        |

---

## 🧪 How It Works

1. 📂 Load the CIFAR-10 dataset (32x32 color images across 10 classes)
2. 🔍 Normalize pixel values to [0,1] and one-hot encode labels
3. 🔁 Apply data augmentation to prevent overfitting
4. 🧱 Build a multi-layer CNN with:
   - Conv2D layers + BatchNormalization
   - MaxPooling2D and Dropout layers
   - L2 kernel regularization
5. 🛠️ Train with Adam optimizer and learning rate scheduler
6. 📈 Plot training and validation accuracy curves
7. 📊 Generate and visualize a confusion matrix with class labels
8. 🔬 Compare original CNN vs. Transfer Learning model performance

---

## 💻 Notebook Contents

- `CIFAR10_CNN_Image_Classification.ipynb`
  - [x] Data loading and preprocessing
  - [x] Data augmentation
  - [x] CNN model building with improvements
  - [x] Training with callbacks
  - [x] Evaluation (accuracy plots + confusion matrix)
  - [x] Model saving and reloading
  - [x] Transfer Learning model evaluation (bonus)

---

## 🧠 Sample Results

| Model                    | Test Accuracy |
|---------------------------|---------------|
| Improved CNN Model        | ~82%          |
| Transfer Learning Model   | ~85%          |

- 🎯 Data augmentation and regularization helped the CNN generalize better.
- 📊 Transfer learning still outperforms slightly, showing strong feature reuse.

---

## ⚠️ Known Issues / Limitations

- ❌ Overfitting still possible if training too many epochs without early stopping
- 🔁 CIFAR-10 is small; larger datasets (like ImageNet) needed for real-world robustness
- ⚡ Training on CPU may be slow (Colab GPU recommended)

---

## 📈 Improvements & Next Steps

- 🔍 Try more aggressive augmentation (zoom, brightness shift)
- 🏗️ Implement Transfer Learning with ResNet50, EfficientNet
- 🚀 Use learning rate warmup and cosine annealing for better training
- 🧪 Add early stopping and model checkpoint callbacks
- 📦 Deploy the model as a simple web app with Streamlit or Gradio

---

## 🚀 Try It Yourself

Install necessary packages first:
```bash
pip install tensorflow numpy matplotlib seaborn scikit-learn
```

And make sure you connect your Google Drive if loading/saving models!

---

✅ **All ready!**  
Want me to also suggest a **nice folder layout** (like `/models/`, `/notebooks/`, `/images/`) for this one?  
Or give you a **`.gitignore`** template so your `model_5.h5` file doesn’t accidentally get committed? 🚀  

Let me know! 🎯  
(Also, send the next `.ipynb` whenever you're ready!)

# Model 
https://drive.google.com/file/d/1PqNRFtKhyFHkJ6srLNgTJqMKHZCXiK77/view?usp=sharing
