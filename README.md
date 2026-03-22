# AI-Based Modulation Classification in Noisy Wireless Systems

## 📌 Overview
This project focuses on classifying wireless modulation schemes under noisy conditions using deep learning.

A hybrid approach combining time-domain (I/Q signals) and frequency-domain (FFT features) is used to improve classification performance.

---

## 🚀 Key Features
- Hybrid feature extraction (Time + Frequency)
- CNN + Bidirectional LSTM architecture
- Achieved ~88% accuracy on RadioML dataset
- Robust performance across different SNR levels

---

## 🧠 Methodology

### Input Data
- I/Q signal samples (time domain)
- FFT magnitude (frequency domain)

### Model
- Conv1D layers for feature extraction
- Bidirectional LSTM for temporal learning
- Dense layers for classification

---

## 📊 Results

### Accuracy vs Epoch
![Accuracy](results/accuracy_plot.png)

### Accuracy vs SNR
![SNR](results/snr_plot.png)

### Confusion Matrix
![Confusion](results/confusion_matrix.png)

---

## 📈 Performance
- Baseline CNN: ~50%
- CNN + LSTM: ~55%
- Hybrid Model: ~88%

---

## ⚙️ Technologies Used
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib

---

## 📡 Applications
- Wireless communication systems (5G/6G)
- Software Defined Radio (SDR)
- Spectrum monitoring
- Military signal intelligence

---

## 📂 How to Run

```bash
pip install -r requirements.txt
