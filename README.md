# 🚦 **SISTEM DETEKSI TEXT ADUAN TRANSPORTASI DAN LALU LINTAS OTOMATIS**
Sistem ini merupakan aplikasi berbasis Command Line Interface (CLI) yang dirancang untuk mendeteksi apakah suatu teks mengandung aduan terkait transportasi dan lalu lintas atau tidak. Sistem ini memanfaatkan Natural Language Processing (NLP) dan Machine Learning (ML) untuk mengklasifikasikan input teks secara otomatis dan real-time.

## 🧠 **TEKNOLOGI & MODEL**
- ✅ **Bahasa Pemrograman:** Python
- ✅ **NLP Libraries:** Sastrawi, NLTK
- ✅ **Model ML:** XGBoost Classifier
- ✅ **Preprocessing:** Slang normalization, stopword removal, stemming
- ✅**Booster Logic:**
    - Regex pattern booster
    - Token pair booster
    - Kata kunci penting
- ✅ **Vectorizer:** Counvectorizer + booster feature

--- 

## ✨ **FITUR UTAMA**
- 🔍 **Deteksi Aduan Otomatis** dari teks pengguna
- 🧹 **Preprocessing Lengkap**: slang correction, stemming, dan filtering kata penting
- ⚡ **Real-time Prediction** dengan estimasi waktu inferensi
- 📊 **Hasil Detail**:
    - Teks asli 
    - Label klasifikasi (Aduan / Bukan Aduan)
    - Probabilitas prediksi
    - Panjang teks 
    - Waktu prediksi
    - Durasi prediksi
- 🛡️ **Booster Pattern** untuk menangkap pola kritis
- 🎮 CLI interaktif dengan banner dan loading animasi

---

## ▶️ **CARA PENGGUNAAN**
### **1. Clone Repository**
```bash
git clone https://github.com/username/nama-repo-anda.git
cd nama-repo-anda
```
### **2. Persiapan**
Pastikan Python 3.8+ sudah terinstal. Install dependensi:
```bash
pip install -r requirements.txt
```
### **3. Jalankan Skrip Python**
```bash
python detect_aduan.py
```
Lalu masukkan kalimat aduan seperti contoh:
```bash
Di daerah Ketintang Timur Surabaya telah terjadi kecelakaan yang melibatkan 2 pengendara motor
```

---

## 🧪 **CONTOH OUTPUT**
```bash
================================================================
                                                            
    🔍 SISTEM DETEKSI ADUAN TRANSPORTASI DAN LALU LINTAS OTOMATIS                     
    ════════════════════════════════════════════════════════════                

    📊 Powered by Machine Learning & NLP                     
    🚀 Enhanced CLI Interface                                 
    ⚡ Real-time Text Analysis                                
                                                            
================================================================

✅ Menyiapkan model & data Complete!

📢 Sistem siap digunakan. Ketik 'exit' untuk keluar.
==================================================================
🕓 Waktu Prediksi        : 2025-08-05 05:02:36
🗒️  Teks Asli            : Di daerah Ketintang Timur Surabaya telah terjadi kecelakaan yang melibatkan 2 pengendara motor
👉 Label                 : Aduan
🔢 Probabilitas          : 1.0000
🧮 Panjang Teks          : 94 karakter
⏱️  Durasi Prediksi      : 0.0002 detik
------------------------------------------------------------------
👋 Terima kasih. Sampai jumpa.
```


---

## 📧 KONTAK
Jika ada pertanyaan atau kerja sama, silakan hubungi:

📩 **Email**   : [ihakam93@gmail.com]  
🐙 **GitHub**  : [github.com/username](https://github.com/IqbalHakam123)  
🌐 **LinkedIn**:[ linkedin.com/in/username](https://www.linkedin.com/in/iqbal-hakam)

---

## 📌 Catatan Penting
✅ Aplikasi ini boleh digunakan oleh siapa saja untuk keperluan riset, pengembangan, maupun produksi dengan syarat mencantumkan atribusi kepada pembuat asli.

❌ Tidak diperkenankan memodifikasi dan mengklaim sistem ini sebagai buatan sendiri tanpa izin.

---
