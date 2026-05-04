# 📊 Sentiment Analysis on E-commerce Reviews using LSTM

## 📌 Overview
Project ini bertujuan untuk menganalisis sentimen ulasan pelanggan pada platform e-commerce menggunakan pendekatan Natural Language Processing (NLP) dan model Long Short-Term Memory (LSTM).

Dengan banyaknya data review pelanggan, analisis manual menjadi tidak efisien. Model ini dibangun untuk mengklasifikasikan sentimen secara otomatis menjadi positif atau negatif.

---

## 🎯 Objectives
- Mengklasifikasikan sentimen ulasan pelanggan
- Mengidentifikasi kualitas produk berdasarkan review
- Memberikan insight untuk pengambilan keputusan bisnis

---

## 📂 Dataset
- Sumber: Tokopedia (Scraping / API)
- Bahasa: Indonesia
- Jumlah data: [ISI JUMLAH DATASET]

### Contoh Data
| Review | Sentimen |
|--------|---------|
| Barang bagus dan cepat sampai | Positif |
| Pengiriman lama dan packing buruk | Negatif |

---

## ⚙️ Data Preprocessing
Tahapan preprocessing:
- Text cleaning (hapus simbol, angka, dll)
- Case folding
- Tokenization
- Stopword removal
- Stemming

---

## 🤖 Modeling
Model yang digunakan:
- Embedding Layer
- Bidirectional LSTM
- Dense Layer

Framework & Library:
- Python
- TensorFlow / Keras

---

## 📈 Model Evaluation
Metrik evaluasi:
- Accuracy
- Loss
- Confusion Matrix

### Hasil
- Accuracy: [ISI AKURASI]
- Model mampu mengklasifikasikan sentimen dengan performa yang baik

---

## 🔍 Results & Insights
- Mayoritas ulasan pelanggan bersentimen positif
- Keluhan utama:
  - Pengiriman
  - Kualitas produk tertentu

---

## 💡 Business Recommendations
- Meningkatkan kualitas pengiriman/logistik
- Evaluasi produk dengan sentimen negatif tinggi
- Monitoring sentimen pelanggan secara berkala

---

## 🚀 Future Improvements
- Menggunakan model lain (CNN, Transformer)
- Menambah jumlah dataset
- Hyperparameter tuning lebih lanjut

---

## 🛠️ Tech Stack
- Python
- TensorFlow / Keras
- Pandas
- NumPy
- Matplotlib / Seaborn
