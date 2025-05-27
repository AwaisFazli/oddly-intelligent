# is-even-ai

> 🧠 A neural network that determines whether a number is **even or odd** — because using `% 2` is just too mainstream.

---

## 🧩 Overview

`is-even-ai` is a TensorFlow-based deep learning model trained to classify integers as **even** or **odd** based on their 17-bit binary representations. While the task itself is trivial, this project serves as a satirical demonstration of how modern AI can be applied — even when it absolutely shouldn't be.

Because if you’re not using neural networks to solve simple problems, are you even doing AI?

---

## 📊 Model Architecture

The model consists of:

- Input Layer: 17 binary features (representing integers from 1 to 99,999)
- Hidden Layer 1: Dense(16), ReLU activation
- Hidden Layer 2: Dense(8), ReLU activation
- Output Layer: Dense(1), Sigmoid activation

Compiled using `binary_crossentropy` loss and the `adam` optimizer.

---

## 🧠 Training

Trained on ~100,000 integers, split into 80/20 training/testing datasets.

Achieved:
- ~99.99% validation accuracy
- Infinite developer satisfaction

---
