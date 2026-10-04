# 🧠 Deep Learning Fundamentals

> **From understanding the neuron to training neural networks — learning Deep Learning by building it practically.**

A hands-on **Deep Learning fundamentals project** focused on understanding the core concepts behind neural networks through practical implementations, experiments, and model training.

This repository documents my practical exploration of Deep Learning — starting with a **Perceptron implemented from scratch** and progressing through **activation functions, MLP forward propagation, loss functions, gradient descent, backpropagation, binary classification, regularization, and gradient-related problems**.

The goal is to understand not only **how to use Deep Learning frameworks**, but also **what happens inside a neural network during learning and prediction**.

---

## 📌 About This Project

Deep Learning models can appear complex when viewed only through high-level frameworks. This project focuses on understanding their fundamental building blocks step by step.

The practicals begin with simple mathematical implementations using **Python and NumPy**, where the internal logic of neural networks can be observed directly.

The later practicals move toward **TensorFlow and Keras**, where complete neural network models are built, trained, validated, and evaluated.

### Learning Progression

```text
Artificial Neuron
       ↓
Perceptron
       ↓
Activation Functions
       ↓
MLP
       ↓
Forward Propagation
       ↓
Loss Functions
       ↓
Gradient Descent
       ↓
Backpropagation
       ↓
Neural Network Training
       ↓
Regularization
       ↓
Gradient Problems
```

---

# 🔬 Practical Implementations

## 01 — Perceptron From Scratch

Built a basic Perceptron using Python and NumPy to understand how an artificial neuron processes input data.

### Concepts

- Inputs
- Weights
- Bias
- Weighted Sum
- Step Activation Function
- Prediction
- Linear Decision Boundary

This practical establishes the foundation for understanding how a neural network neuron works.

---

## 02 — Perceptron Learning Rule

Implemented the Perceptron learning rule to understand how model parameters are updated based on prediction errors.

### Concepts

- Prediction
- Error Calculation
- Learning Rate
- Weight Updates
- Bias Updates
- Epochs

This practical demonstrates the basic learning mechanism where the model adjusts its parameters based on its mistakes.

---

## 03 — Activation Functions

Implemented and visualized commonly used activation functions to understand how neural networks introduce non-linearity.

### Implemented

- Sigmoid
- Tanh
- ReLU
- Leaky ReLU

The practical explores the behavior of different activation functions and their importance in neural networks.

---

## 04 — MLP Forward Propagation

Implemented the forward propagation process of a **Multi-Layer Perceptron (MLP)**.

```text
Input Layer
     ↓
Hidden Layer
     ↓
Output Layer
```

### Concepts

- Input Layer
- Hidden Layer
- Output Layer
- Weights
- Biases
- Weighted Sum
- Activation
- Forward Propagation

This practical demonstrates how information flows through a neural network to produce an output.

---

## 05 — Loss Functions

Explored different loss functions used to measure the difference between actual and predicted values.

### Implemented

- Mean Squared Error (MSE)
- Binary Cross-Entropy
- Categorical Cross-Entropy

Loss functions provide the measure that helps determine how well a model is performing during training.

---

## 06 — Gradient Descent

Implemented Gradient Descent from scratch to understand how model parameters are updated to reduce loss.

### Concepts

- Gradient
- Learning Rate
- Weight Updates
- Loss Reduction
- Convergence
- Batch Gradient Descent
- Stochastic Gradient Descent
- Mini-Batch Gradient Descent

The practical demonstrates the fundamental optimization process behind neural network training.

---

## 07 — Backpropagation From Scratch

Implemented Backpropagation using NumPy to understand how neural networks calculate gradients and update their parameters.

### Concepts

- Forward Propagation
- Loss Calculation
- Chain Rule
- Gradient Calculation
- Weight Gradients
- Bias Gradients
- Backward Propagation
- Parameter Updates

This practical connects the concepts of **loss, gradients, and learning** into one complete training process.

---

## 08 — MLP Binary Classification

Built a complete **MLP binary classification model** using **TensorFlow and Keras**.

### Training Pipeline

```text
Dataset
   ↓
Train / Test Split
   ↓
Feature Scaling
   ↓
MLP Architecture
   ↓
Forward Propagation
   ↓
Loss Calculation
   ↓
Backpropagation
   ↓
Adam Optimizer
   ↓
Model Training
   ↓
Validation
   ↓
Prediction
   ↓
Evaluation
```

### Model Components

- Dense Neural Network Layers
- ReLU Activation
- Sigmoid Output
- Binary Cross-Entropy
- Adam Optimizer
- Mini-Batch Training
- Validation

### Evaluation

- Accuracy
- Confusion Matrix
- Classification Report
- Training Curves
- Validation Curves

---

## 09 — Overfitting & Regularization

Explored how neural networks can overfit training data and how regularization techniques can improve generalization.

### Techniques

- Dropout
- L2 Regularization
- Early Stopping

The practical compares training and validation behavior to understand the difference between **memorizing training data** and **learning patterns that generalize**.

---

## 10 — Vanishing & Exploding Gradients

Explored two important challenges that can occur during neural network training.

### Vanishing Gradients

Gradients become very small as they propagate backward through layers, making learning difficult for earlier layers.

### Exploding Gradients

Gradients become excessively large, resulting in unstable training and very large parameter updates.

### Concepts

- Sigmoid Gradients
- Tanh Gradients
- ReLU Gradients
- Vanishing Gradients
- Exploding Gradients
- Gradient Clipping

---

# 🧠 Core Concepts Covered

### Neural Network Fundamentals

`Neuron` • `Weights` • `Bias` • `Weighted Sum` • `Perceptron` • `MLP`

### Neural Network Training

`Forward Propagation` • `Backpropagation` • `Chain Rule` • `Gradients` • `Gradient Descent` • `Weight Updates`

### Activation Functions

`Sigmoid` • `Tanh` • `ReLU` • `Leaky ReLU` • `Softmax`

### Loss Functions

`MSE` • `Binary Cross-Entropy` • `Categorical Cross-Entropy`

### Training Challenges

`Overfitting` • `Vanishing Gradients` • `Exploding Gradients` • `Learning Rate`

### Regularization

`Dropout` • `L2 Regularization` • `Early Stopping` • `Gradient Clipping`

---

# 🛠️ Technologies & Tools

| Category | Technologies |
|---|---|
| **Language** | Python |
| **Numerical Computing** | NumPy |
| **Data Handling** | Pandas |
| **Visualization** | Matplotlib |
| **Machine Learning** | Scikit-learn |
| **Deep Learning** | TensorFlow, Keras |
| **Development** | VS Code, Jupyter Notebook |
| **Cloud Notebook** | Google Colab |
| **Version Control** | Git, GitHub |

---

# 📂 Repository Structure

```text
deep-learning-journey/
│
├── Deep-Learning-Fundamentals/
│   │
│   ├── Perceptron From Scratch
│   ├── Perceptron Learning Rule
│   ├── Activation Functions
│   ├── MLP Forward Propagation
│   ├── Loss Functions
│   ├── Gradient Descent
│   ├── Backpropagation From Scratch
│   ├── MLP Binary Classification
│   ├── Overfitting & Regularization
│   └── Vanishing & Exploding Gradients
│
└── README.md
```

The practical files may be organized as notebooks or Python files depending on the implementation environment.

---

# 🔄 How a Neural Network Learns

The core learning process explored throughout these practicals can be summarized as:

```text
             INPUT
               │
               ▼
      ┌─────────────────┐
      │ Forward Pass    │
      └────────┬────────┘
               │
               ▼
          Prediction
               │
               ▼
        Loss Calculation
               │
               ▼
      ┌─────────────────┐
      │ Backpropagation │
      └────────┬────────┘
               │
               ▼
        Gradient Calculation
               │
               ▼
       Weight / Bias Update
               │
               ▼
          Next Epoch
               │
               └───────────────► Repeat
```

This cycle is repeated during training so that the model gradually improves its predictions.

---

# 📊 Learning Progress

| # | Practical | Status |
|---:|---|:---:|
| 01 | Perceptron From Scratch | ✅ |
| 02 | Perceptron Learning Rule | ✅ |
| 03 | Activation Functions | ✅ |
| 04 | MLP Forward Propagation | ✅ |
| 05 | Loss Functions | ✅ |
| 06 | Gradient Descent | ✅ |
| 07 | Backpropagation From Scratch | ✅ |
| 08 | MLP Binary Classification | ✅ |
| 09 | Overfitting & Regularization | ✅ |
| 10 | Vanishing & Exploding Gradients | ✅ |

---

# 🎯 What I Learned

Through these practical implementations, I gained hands-on understanding of:

- How an artificial neuron works
- How weights and biases influence predictions
- How a Perceptron learns from errors
- Why activation functions are required
- How information moves through an MLP
- How loss functions measure model performance
- How Gradient Descent minimizes loss
- How Backpropagation calculates gradients
- How neural network parameters are updated
- How to build an MLP using TensorFlow/Keras
- How to identify and handle overfitting
- How regularization improves generalization
- Why vanishing and exploding gradients occur
- How gradient clipping can help stabilize training

---

# 💻 Development Approach

This project follows a **concept → implementation → experimentation → evaluation** approach.

```text
Understand
    ↓
Implement
    ↓
Experiment
    ↓
Observe
    ↓
Evaluate
    ↓
Improve
```

The from-scratch implementations help build an understanding of the underlying mathematics and logic, while TensorFlow/Keras implementations provide practical experience with modern Deep Learning workflows.

---

# 🔮 What's Next?

After completing the fundamentals, the next stage of this repository will move toward **Deep Learning optimization and advanced architectures**.

Planned areas include:

- SGD with Momentum
- RMSprop
- Adam
- Learning Rate Scheduling
- Gradient Clipping
- Convolutional Neural Networks
- Image Classification
- RNN
- LSTM
- GRU
- Time-Series Deep Learning
- Transfer Learning
- Attention Mechanism
- Transformers
- Generative AI

---

# 🌱 Project Purpose

This project represents my effort to build a strong foundation in **Deep Learning through practical implementation**.

Rather than treating neural networks as black-box models, I am focusing on understanding the process behind them — from **inputs, weights, and biases to forward propagation, loss calculation, gradients, backpropagation, and parameter updates**.

These fundamentals form the base for progressing toward more advanced areas of **Artificial Intelligence, Computer Vision, Natural Language Processing, Generative AI, and modern neural network architectures**.


---

## 🚀 Continuous Learning

> **Learn the concept. Understand the logic. Build it yourself. Improve with every experiment.**

**This repository is not just a collection of notebooks — it is a record of my progress from understanding the fundamentals of neural networks to building practical Deep Learning solutions.**

⭐ **Understand. Implement. Experiment. Evolve.**
