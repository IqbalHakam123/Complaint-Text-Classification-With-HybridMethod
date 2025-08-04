🚦 SISTEM DETEKSI ADUAN TRANSPORTASI DAN LALU LINTAS OTOMATIS

Sistem ini merupakan aplikasi berbasis Command Line Interface (CLI) yang dirancang untuk mendeteksi apakah suatu teks mengandung aduan terkait transportasi dan lalu lintas atau tidak. Sistem ini memanfaatkan Natural Language Processing (NLP) dan Machine Learning (ML) untuk mengklasifikasikan input teks secara otomatis dan real-time.

🧠 Teknologi & Model

Bahasa Pemrograman: Python

NLP Libraries: Sastrawi, NLTK

Model ML: XGBoost Classifier

Preprocessing: Slang normalization, stopword removal, stemming

Booster Logic:

Regex pattern booster

Token pair booster

Kata kunci penting

Vectorizer: TF-IDF + booster feature

✨ Fitur Utama

🔍 Deteksi Aduan Otomatis dari teks pengguna

🧹 Preprocessing Lengkap: slang correction, stemming, dan filtering kata penting

⚡ Real-time Prediction dengan estimasi waktu inferensi

📊 Hasil Detail:

Teks asli & teks bersih

Label klasifikasi (Aduan / Bukan Aduan)

Probabilitas prediksi

Panjang teks & jumlah token

Waktu prediksi (durasi)

🛡️ Booster Pattern untuk menangkap pola kritis

🎮 CLI interaktif dengan banner dan loading animasi

▶️ Cara Penggunaan

1. Clone Repo

git clone https://github.com/username/nama-repo-anda.git
cd nama-repo-anda

2. Persiapan

Pastikan Python 3.8+ sudah terinstal. Install dependensi:

pip install -r requirements.txt

3. Jalankan Aplikasi

python detect_aduan.py

Lalu masukkan kalimat aduan seperti contoh:

📝 Masukkan teks: lampu lalu lintas di perempatan mati total

🧪 Contoh Output

================================================================
    🔍 SISTEM DETEKSI ADUAN TRANSPORTASI DAN LALU LINTAS OTOMATIS                     
================================================================
⏳ Menyiapkan model & data...
✅ Menyiapkan model & data Complete!

📢 Sistem siap digunakan. Ketik 'exit' untuk keluar.

📝 Masukkan teks: lampu lalu lintas di perempatan mati total

==================================================================
🕒 Waktu Prediksi        : 2025-07-29 10:24:12
📜  Teks Asli            : lampu lalu lintas di perempatan mati total
🧹 Teks Setelah Bersih   : lampu lintas perempatan mati total
👉 Label                 : Aduan
🔢 Probabilitas          : 0.8643
🧮 Panjang Teks          : 45 karakter
📏 Jumlah Token          : 5 kata
⏱️  Durasi Prediksi      : 0.1121 detik
--------------------------------------------------

📬 Kontak

👤 Nama: [Nama Anda]📧 Email: your.email@example.com🐙 GitHub: github.com/username🌐 LinkedIn: linkedin.com/in/username

📌 Catatan Penting

✅ Aplikasi ini boleh digunakan oleh siapa saja untuk keperluan riset, pengembangan, maupun produksi dengan syarat mencantumkan atribusi kepada pembuat asli.❌ Tidak diperkenankan memodifikasi dan mengklaim sistem ini sebagai buatan sendiri tanpa izin.
