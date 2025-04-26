# Inception Network (GoogleNet) Implementation in TensorFlow

This repository contains a TensorFlow/Keras implementation of the **Inception Network**, famously known as **GoogleNet**, designed for efficient deep learning with reduced computational cost.

The notebook walks through the core building blocks of Inception modules and constructs a small version of the Inception architecture.

---

## 📖 About Inception Networks

**Inception Networks** introduced the idea of parallel convolutional layers of different sizes in a single module, allowing the network to capture features at multiple scales without heavily increasing computation.

Key highlights:
- Introduces the **Inception Module**.
- Combines **multiple filter sizes (1x1, 3x3, 5x5)** in parallel.
- Reduces computation using **1x1 convolutions** (bottleneck layers).
- Winner of the **ILSVRC 2014** competition.

**Reference Paper:**  
*"Going Deeper with Convolutions"*  
[arXiv:1409.4842](https://arxiv.org/abs/1409.4842)

---

## 🛠 What’s inside

- Custom implementation of the **Inception Module**.
- Assembly of the full **Inception Network** structure.
- Easy-to-read and modify TensorFlow/Keras code.
- Good starting point for further extensions (like Inception-v2, v3).

---
