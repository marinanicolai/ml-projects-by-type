# Artificial Neural Networks (ANN) - Perceptron vs. Multi-Layer Networks

This repository provides an introduction to **two types of Artificial Neural Networks**:

1. **Single-Layer Perceptron (SLP)**
2. **Multi-Layer Neural Network (MLP)**

It includes Jupyter notebooks that demonstrate both models and their configurations.

---

## 📘 Notebooks

### `26.04_Perceptron_Based_Classification_Model.ipynb`

This notebook demonstrates a **Single-Layer Perceptron**, the simplest form of an artificial neural network. It contains:

- A single layer of weights connecting input features to the output
- A binary classification task
- Core concepts: weight update, bias, learning rate, activation (step) function

🧠 Ideal for: Understanding the **fundamentals of a neuron and supervised learning**.

---

### `26.06_Configure_Neural_Network_and_Activation_Function.ipynb`

This notebook demonstrates a **Multi-Layer Neural Network**, commonly called a **Multi-Layer Perceptron (MLP)**. It includes:

- One or more hidden layers
- Non-linear activation functions (e.g., ReLU, Sigmoid)
- Configurable architecture (number of neurons/layers)
- Forward and backward propagation

⚙️ Ideal for: Learning how deep networks solve **complex non-linear classification and regression problems**.

---

## 🔬 Key Differences

| Feature                    | Single-Layer Perceptron | Multi-Layer Neural Network |
|---------------------------|-------------------------|----------------------------|
| Layers                    | 1 (Input → Output)      | ≥2 (Input → Hidden → Output) |
| Activation Function       | Usually Step            | ReLU, Sigmoid, Tanh, etc.  |
| Learn Non-linear Patterns | ❌                      | ✅                         |
| Use Case                  | Simple binary tasks     | Complex real-world tasks   |

---

## 📊 Visual Summary

![ANN Comparison](assets/ann_comparison_diagram.png)


---

📚 References
Rosenblatt, F. (1958). The Perceptron: A Probabilistic Model for Information Storage and Organization in the Brain.

Goodfellow, Bengio, & Courville. (2016). Deep Learning. MIT Press.


