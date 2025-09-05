# Neural Network from Scratch (MNIST Classification)

This repository implements a **fully custom feedforward neural network** (no deep-learning frameworks) to classify handwritten digits using scikit-learn’s **Digits** dataset (8×8 images; a small MNIST-like dataset).  
The notebook walks through preprocessing, activation functions (and their derivatives), training, hyperparameter experiments, and comparisons across **Sigmoid**, **ReLU**, and **Tanh** networks.

---

## 📌 Features
- Load and explore the **MNIST** dataset (`sklearn.datasets.load_digits`)
- Preprocessing:
  - One-hot encoding of labels
  - Train/test split
  - Feature scaling (`StandardScaler`)
- From-scratch neural network:
  - Forward & backward propagation
  - Cross-entropy/hinge-style loss (per notebook)
  - Weight updates via gradient descent
  - Support for **Sigmoid**, **ReLU**, and **Tanh** activations
- Hyperparameter experiments (learning rate, epochs, hidden size, etc.)
- Evaluation with accuracy metrics
- Clear notes on findings and trade-offs

---

## ⚙️ Requirements
Install the minimal dependencies with:

```bash
pip install numpy pandas matplotlib scikit-learn
```

## How to Run
1. Clone the repository
2. Launch the notebook
3. Run all cells
