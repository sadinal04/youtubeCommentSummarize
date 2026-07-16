# 🎥 YouTube Comment Summarizer using Fine-Tuned IndoT5

## 📌 Deskripsi Project

**YouTube Comment Summarizer** adalah sistem berbasis **Natural Language Processing (NLP)** yang dirancang untuk menghasilkan ringkasan otomatis dari komentar video YouTube berbahasa Indonesia. Project ini menggunakan model **IndoT5 (`cahya/t5-base-indonesian-summarization-cased`)** yang di-*fine-tuning* menggunakan dataset komentar YouTube sehingga mampu menghasilkan ringkasan yang lebih relevan dan informatif.

---

## 🎯 Tujuan

- Mengotomatisasi proses peringkasan komentar YouTube.
- Membantu memahami opini publik tanpa membaca ribuan komentar.
- Mengimplementasikan proses fine-tuning model Transformer untuk tugas text summarization.

---

## ⚙️ Teknologi yang Digunakan

- Python
- PyTorch
- Hugging Face Transformers
- IndoT5 (`cahya/t5-base-indonesian-summarization-cased`)
- YouTube Data API
- Pandas
- NLTK
- Sastrawi
- Scikit-learn
- Jupyter Notebook

---

## 🧠 Cara Kerja Sistem

### 1. Data Collection
Mengambil komentar dari video YouTube menggunakan **YouTube Data API**.

### 2. Text Preprocessing
- Case Folding
- Cleaning Text
- Stopword Removal
- Tokenization
- Stemming

### 3. Fine-Tuning
Melakukan fine-tuning model **IndoT5** menggunakan dataset komentar YouTube beserta ringkasan sebagai target.

### 4. Inference
Model menghasilkan ringkasan otomatis yang mewakili opini utama pengguna.

---

## 📊 Dataset

Dataset terdiri dari komentar video YouTube berbahasa Indonesia yang dikumpulkan menggunakan **YouTube Data API**. Setiap data dipasangkan dengan ringkasan sebagai target untuk proses fine-tuning model.

---

## 🚀 Fitur

- 📥 Mengambil komentar dari YouTube
- 🧹 Preprocessing teks otomatis
- 🤖 Fine-tuning model IndoT5
- 📝 Ringkasan komentar secara otomatis
- 📊 Membantu analisis opini publik

---

## 🖥️ Cara Menjalankan

```bash
git clone https://github.com/sadinal04/youtubeCommentSummarize.git
cd youtubeCommentSummarize
pip install -r requirements.txt
jupyter notebook
```

---

## 📈 Output

- Ringkasan otomatis dari kumpulan komentar YouTube.
- Insight utama mengenai opini pengguna terhadap suatu video.

---

## 📌 Keunggulan

- Menggunakan model Transformer yang telah di-fine-tuning.
- Mendukung ringkasan komentar berbahasa Indonesia.
- Dapat diterapkan untuk analisis opini publik dan social media analytics.

---

## 🔮 Pengembangan Selanjutnya

- Sentiment Analysis
- Aspect-Based Sentiment Analysis
- Web Deployment menggunakan Streamlit/FastAPI
- Ringkasan Multi-Video
- Visualisasi Insight Dashboard

---

## 👤 Author

**Sadinal Mufti**  
Data Scientist | Machine Learning Engineer | AI Enthusiast
