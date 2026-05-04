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
- Jumlah data: 10825

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
<img width="1165" height="470" alt="image" src="https://github.com/user-attachments/assets/339b1501-1217-4f81-af3e-7ef157cab1d3" />

### Hasil
<img width="649" height="547" alt="image" src="https://github.com/user-attachments/assets/dc566d29-5365-4d0d-8008-e4a94ca74e29" />

- Accuracy: 98%
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
