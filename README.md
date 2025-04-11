# 🧠 Handwritten Digit Classification using ANN

This project demonstrates a neural network built with TensorFlow and Keras to classify handwritten digits from the MNIST dataset. The model is trained on 60,000 images and evaluated on 10,000 test images to showcase fundamental image classification capabilities using Artificial Neural Networks (ANNs).

---

## 📊 Dataset

- **Source:** MNIST Dataset from `keras.datasets`
- **Images:** 28x28 grayscale pixels
- **Train Set:** 60,000 images  
- **Test Set:** 10,000 images

---

## 🚀 Model Architecture

- **Input Layer:** 784 neurons (flattened 28x28 image)  
- **Hidden Layer:** 100 neurons, ReLU activation  
- **Output Layer:** 10 neurons (digit classes 0–9), Softmax activation  
- **Loss Function:** Sparse Categorical Crossentropy  
- **Optimizer:** Adam  

---

## ✅ Accuracy Matrix

| Metric         | Value     |
|----------------|-----------|
| Test Accuracy  | **97.68%** |
| Loss           | 0.087 |

---

## 📦 Tech Stack

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib and Seaborn (for visualization)

---
## Heat-Map for Final output:
![image](https://github.com/user-attachments/assets/b82c6174-73b6-4159-93b3-f008fcdc1ab9)

---

## 🔮 Future Improvements

- Perform hyperparameter tuning for improved accuracy  
- Experiment with CNN architecture to boost performance  
- Add dropout layers to reduce overfitting  
- Visualize predictions and misclassified digits  
- Deploy the model using Flask or Streamlit for interactive web app  
