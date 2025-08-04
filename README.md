# 🚦 **SISTEM DETEKSI ADUAN TRANSPORTASI DAN LALU LINTAS OTOMATIS**

Sistem ini merupakan aplikasi berbasis Command Line Interface (CLI) yang dirancang untuk mendeteksi apakah suatu teks mengandung aduan terkait transportasi dan lalu lintas atau tidak. Sistem ini memanfaatkan Natural Language Processing (NLP) dan Machine Learning (ML) untuk mengklasifikasikan input teks secara otomatis dan real-time.

## 🧠 **Teknologi & Model**
-  **Bahasa Pemrograman:** Python
-  **NLP Libraries:** Sastrawi, NLTK
-  **Model ML:** XGBoost Classifier
-  **Preprocessing:** Slang normalization, stopword removal, stemming
-  **Booster Logic:**
  - Regex pattern booster
  - Token pair booster
  - Kata kunci penting
-  **Vectorizer:** TF-IDF + booster feature

## ✨ Fitur Utama

- 🔍 **Deteksi Aduan Otomatis** dari teks pengguna
- 🧹 **Preprocessing Lengkap**: slang correction, stemming, dan filtering kata penting
- ⚡ **Real-time Prediction** dengan estimasi waktu inferensi
- 📊 **Hasil Detail**:
   - Teks asli & teks bersih
   - Label klasifikasi (Aduan / Bukan Aduan)
   - Probabilitas prediksi
   - Panjang teks & jumlah token
   - Waktu prediksi (durasi)
- 🛡️ **Booster Pattern** untuk menangkap pola kritis
- 🎮 CLI interaktif dengan banner dan loading animasi
