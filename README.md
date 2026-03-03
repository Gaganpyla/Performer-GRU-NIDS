# Network Intrusion Detection Using a Performer-GRU Attention Architecture

## 📌 Overview
This project presents a deep learning-based Network Intrusion Detection System (NIDS) using a hybrid **Performer Attention + GRU architecture**.

The model combines:
- 🔹 Performer (efficient linear attention)
- 🔹 Gated Recurrent Units (GRU)
- 🔹 Attention-based feature learning

to efficiently detect malicious network traffic.

---

## 🧠 Architecture

Input Features  
→ Linear Embedding  
→ Performer Attention Layer  
→ GRU Layer  
→ Fully Connected Layer  
→ Softmax Output  

---

## 📊 Dataset

Dataset used:
- CICIDS2017 / NSL-KDD / UNSW-NB15 (update with yours)

Preprocessing steps:
- Handling missing values
- Feature scaling (StandardScaler)
- Label encoding
- Train/Test split

---

## 🚀 Installation

```bash
git clone https://github.com/yourusername/performer-gru-nids.git
cd performer-gru-nids
pip install -r requirements.txt
