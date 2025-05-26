# PRODIGY_ML_03

# 🐱🐶 Cats vs Dogs Classification using SVM

This project applies a **Support Vector Machine (SVM)** classifier to distinguish between images of cats and dogs using the popular `cats_vs_dogs` dataset from **TensorFlow Datasets**.

---

## 🧠 Objective

To build a fast and lightweight binary classifier using **grayscale image features** and **SVM** for recognizing cats vs dogs.

---

## 🧰 Technologies Used

- `tensorflow-datasets` – Load the dataset  
- `OpenCV` – Image preprocessing (grayscale + resize)  
- `scikit-learn` – SVM model, train/test split, evaluation  
- `matplotlib` – Image visualization

---

## 📦 Dataset Info

- **Dataset:** [TensorFlow Datasets - cats_vs_dogs](https://www.tensorflow.org/datasets/catalog/cats_vs_dogs)
- **Classes:** Cat, Dog
- **Images Used:** 2,000 (for speed & simplicity)
- **Preprocessing:**
  - Convert RGB to Grayscale
  - Resize to `64x64`
  - Flatten into 1D vectors

---

## ⚙️ How It Works

1. Load and preprocess 2,000 images (grayscale & resized).
2. Flatten each image for SVM input.
3. Split into 80% training and 20% testing.
4. Train an SVM classifier with a linear kernel.
5. Evaluate using **accuracy** and **classification report**.
6. Display sample test images with predictions.

