# PG-NET: Performer-GRU Based Network Intrusion Detection System

## 📌 Overview

PG-NET is a deep learning-based Network Intrusion Detection System (IDS) that combines:

- 🔹 Performer (efficient linear self-attention)
- 🔹 Gated Recurrent Units (GRU)
- 🔹 Class-weight balancing
- 🔹 Optimized training pipeline

This implementation includes both:

- ✅ Binary Classification (Attack vs Normal)
- ✅ Multiclass Classification (Multiple attack categories)

The architecture is designed to be scalable, efficient, and publication-ready.

---

## 🧠 Architecture

PG-NET Architecture:

Input Features  
→ Linear Embedding  
→ Performer Attention Layer  
→ GRU Layer  
→ Fully Connected Layer  
→ Softmax Output  

### Why Performer + GRU?

- Performer reduces attention complexity from **O(n²)** to **O(n)**
- GRU captures sequential dependencies in network traffic
- Hybrid design improves detection performance on imbalanced datasets

---


---

## 📊 Dataset

The model is designed for standard IDS datasets such as:

- CICIDS2017  
- NSL-KDD  
- UNSW-NB15  

Dataset loading is handled using `kagglehub`.

### Preprocessing Steps

- Missing value handling
- Feature normalization
- Label encoding
- Train-test split
- Class weight balancing (for imbalanced attacks)

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/PG-NET.git
cd PG-NET
