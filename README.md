# 🎥 YouTube Comment Summarizer

## 📌 Deskripsi Project

**YouTube Comment Summarizer** adalah aplikasi yang dirancang untuk mengekstrak dan merangkum komentar dari video YouTube secara otomatis. Project ini bertujuan membantu pengguna memahami opini, feedback, dan insight dari banyak komentar tanpa harus membaca semuanya secara manual.

Sistem memanfaatkan teknik **Natural Language Processing (NLP)** untuk melakukan preprocessing teks dan menghasilkan ringkasan yang informatif dan relevan.

---

## 🎯 Tujuan

* Mempermudah analisis komentar YouTube dalam jumlah besar
* Menghasilkan ringkasan otomatis dari opini pengguna
* Mengimplementasikan teknik NLP pada data real-world

---

## ⚙️ Teknologi yang Digunakan

* Python
* YouTube Data API
* Pandas
* NLTK / Sastrawi (Text Preprocessing)
* Scikit-learn / Sumy / Transformers (Summarization - opsional tergantung implementasi)
* Jupyter Notebook / Script Python

---

## 🧠 Cara Kerja Sistem

### 1. Ekstraksi Data

* Mengambil komentar dari video YouTube menggunakan **YouTube API**

### 2. Preprocessing

* Case folding (lowercase)
* Menghapus tanda baca dan angka
* Stopword removal
* Tokenisasi & stemming

### 3. Summarization

* Mengolah kumpulan komentar
* Menghasilkan ringkasan inti dari opini pengguna

---

## 📊 Dataset

Dataset berupa komentar dari video YouTube yang diambil secara langsung menggunakan API.

Data yang digunakan meliputi:

* Teks komentar
* Username (opsional)
* Tanggal komentar

---

## 🚀 Fitur Utama

* 🔽 Mengambil komentar dari video YouTube
* 🧹 Preprocessing teks otomatis
* 🧠 Ringkasan komentar secara otomatis
* 📊 Membantu memahami opini publik dengan cepat

---

## 🖥️ Cara Menjalankan Project

1. Clone repository:

```bash id="s9q2pd"
git clone https://github.com/sadinal04/youtubeCommentSummarize.git
```

2. Masuk ke folder project:

```bash id="h3k2lx"
cd youtubeCommentSummarize
```

3. Install dependencies:

```bash id="t8zk1w"
pip install -r requirements.txt
```

4. Jalankan program / notebook:

```bash id="d9q8vm"
jupyter notebook
```

atau

```bash id="a2v6np"
python main.py
```

---

## 📈 Output

* Ringkasan dari kumpulan komentar YouTube
* Insight umum dari opini pengguna

---

## 📌 Keunggulan Project

* Menghemat waktu membaca ribuan komentar
* Menggunakan NLP untuk analisis teks otomatis
* Dapat diterapkan untuk analisis opini publik

---

## 🔮 Pengembangan Selanjutnya

* Sentiment analysis (positif, negatif, netral)
* Visualisasi hasil (wordcloud, grafik)
* Deploy ke web app
* Integrasi dengan multiple video

---

## 👤 Author

**Sadinal Mufti**
Data Science | Machine Learning | AI Enthusiast

---

## 📬 Catatan

Project ini merupakan implementasi konsep **Natural Language Processing (NLP)** dalam menganalisis data komentar dari media sosial (YouTube).
