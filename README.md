
# 🧠 Spam Email Classifier using an Artificial Neural Network (ANN) from Scratch

> A complete implementation of a **Multi-Layer Perceptron (MLP)** built entirely from scratch using **NumPy**—without relying on deep learning frameworks like **PyTorch**, **TensorFlow**, or **Keras**.

## 📌 Overview

This project demonstrates how an Artificial Neural Network learns by implementing every major component manually. Rather than using high-level libraries, the objective was to understand the mathematics and intuition behind neural networks.

The model is trained to classify emails as **Spam** or **Ham (Not Spam)** using TF-IDF features extracted from email text.

---

## 🚀 Features

* ✅ Built completely from scratch using **NumPy**
* ✅ No PyTorch, TensorFlow, or Keras
* ✅ Text preprocessing pipeline
* ✅ TF-IDF feature extraction
* ✅ Custom implementation of:

  * He Weight Initialization
  * Forward Propagation
  * ReLU Activation
  * Sigmoid Activation
  * Binary Cross-Entropy Loss
  * Backpropagation (Chain Rule)
  * Mini-Batch Gradient Descent
* ✅ Training Loss Visualization
* ✅ Spam/Ham Prediction
* ✅ Model Evaluation

---

## 🏗️ Neural Network Architecture

```text
Input Layer (TF-IDF Features)
          │
          ▼
Hidden Layer 1 (64 Neurons)
Activation: ReLU
          │
          ▼
Hidden Layer 2 (32 Neurons)
Activation: ReLU
          │
          ▼
Output Layer (1 Neuron)
Activation: Sigmoid
          │
          ▼
Spam (1) / Ham (0)
```

---

## 📂 Project Workflow

```text
Dataset
   │
   ▼
Data Cleaning
   │
   ▼
TF-IDF Vectorization
   │
   ▼
Train-Test Split
   │
   ▼
Weight Initialization
   │
   ▼
Forward Propagation
   │
   ▼
Binary Cross-Entropy Loss
   │
   ▼
Backpropagation
   │
   ▼
Mini-Batch Gradient Descent
   │
   ▼
Model Training
   │
   ▼
Prediction & Evaluation
```

---

## 🛠️ Tech Stack

* Python
* NumPy
* Pandas
* Matplotlib
* NLTK
* Scikit-learn

---

## 📊 Evaluation Metrics

The model is evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix

---

## 📁 Project Structure

```text
Spam-Email-Classifier-ANN-From-Scratch/
│
├── spam.csv
├── ANN_From_Scratch.ipynb
├── README.md
└── requirements.txt
```

---

## 🎯 Learning Outcomes

This project helped me gain a deeper understanding of:

* How neurons process information
* Matrix operations inside neural networks
* Forward propagation
* Backpropagation using the Chain Rule
* Binary Cross-Entropy Loss
* Gradient Descent optimization
* Mini-Batch Gradient Descent
* Weight initialization techniques
* Building neural networks without deep learning frameworks

---

## 💡 Why Build It from Scratch?

Frameworks like PyTorch and TensorFlow make building neural networks incredibly convenient, but they abstract away the underlying computations.

By implementing everything manually, I developed a much stronger intuition for how neural networks actually learn and how gradients flow through the network during training.

---

## 🔮 Future Improvements

* Add L2 Regularization
* Implement Dropout
* Add Adam Optimizer
* Support Multi-Class Classification
* Build a Streamlit Web Application
* Compare performance with a PyTorch implementation

---

## 🤝 Connect With Me

If you have suggestions, feedback, or ideas for improving this project, feel free to connect or open an issue.

If you found this project helpful, consider giving the repository a ⭐.

