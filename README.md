# 🔁 Recurrent Neural Network (RNN) - Sequence Prediction

This project demonstrates a basic Recurrent Neural Network (RNN) built with TensorFlow and Keras to predict the next number in a sequence. It serves as a beginner-friendly introduction to sequence modeling and the workings of RNNs in time-series or sequential data.

---

## 🧠 Overview

Given a numerical input sequence like `[1, 2, 3]`, the RNN learns to predict the next value in the sequence (e.g., `4`). This is a classic regression problem where the model learns sequential dependencies in time-series data.

---

## 🏗️ Model Architecture

- **Framework:** TensorFlow / Keras
- **Architecture:** Sequential
- **Layers:**
  - `SimpleRNN`: Recurrent layer for sequential learning
  - `Dense`: Output layer for regression

---

## 📊 Dataset

The dataset is synthetically generated:
- Input: Sequences like `[1, 2, 3]`
- Target: The next value, e.g., `4`

```python
# Example:
X = [[1, 2, 3], [2, 3, 4], ...]
y = [4, 5, ...]
