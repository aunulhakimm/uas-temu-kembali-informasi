# 📘 UAS Temu Kembali Informasi  
## Question Answering dan Information Retrieval Putusan PN Denpasar

---

## 📌 Deskripsi Proyek
Proyek ini merupakan implementasi tugas Ujian Akhir Semester mata kuliah **Temu Kembali Informasi** yang berfokus pada pembangunan dan evaluasi sistem **Question Answering (Q&A)** berbasis **Transformer dan Embeddings** pada dokumen putusan pidana khusus narkotika Pengadilan Negeri Denpasar.

Dataset yang digunakan berasal dari hasil **crawling dan ekstraksi dokumen putusan** yang kemudian diolah menjadi dataset **Question–Answer**, dilanjutkan dengan pencarian semantik dan evaluasi performa model menggunakan metrik Information Retrieval.

---

## 👨‍🎓 Disusun Oleh
- **Dio Richard Prastiyo** (202210370311061)  
- **Muhammad Aunul Hakim** (202210370311073)

---

## 🏫 Program Studi
Informatika  
Fakultas Teknik  
Universitas Muhammadiyah Malang

---

## 🧠 Metodologi

### 1️⃣ Crawling dan Ekstraksi Dokumen
- Sumber: Putusan PN Denpasar
- Tahun: 2024–2025
- Jenis: Pidana Khusus (Narkotika)
- Output:
  - File PDF dan TXT
  - Dataset ekstraksi (CSV)

### 2️⃣ Q&A Dataset Generation
- Pertanyaan dan jawaban dibuat berdasarkan hasil ekstraksi dokumen
- Dataset disimpan dalam format CSV
- Model berbasis Transformer digunakan untuk representasi semantik

### 3️⃣ Semantic Information Retrieval
- Model: Sentence-BERT (Multilingual)
- Teknik:
  - Embedding
  - Cosine Similarity
- Output:
  - Jawaban paling relevan terhadap query pengguna

### 4️⃣ Evaluasi Model
- Pertanyaan uji (unseen queries)
- Penilaian berbasis:
  - Precision
  - Recall
  - F1-Score
- Visualisasi:
  - Grafik metrik evaluasi
  - Confusion Matrix
  - Similarity Score

---

## 📊 Hasil Evaluasi
Model Q&A menunjukkan performa yang baik dalam pencarian semantik dengan nilai precision yang tinggi, meskipun masih terdapat keterbatasan dalam recall akibat variasi bahasa hukum.

---

## 🚀 Cara Menjalankan
1. Buka file `.ipynb` di Google Colab  
2. Mount Google Drive  
3. Jalankan notebook secara berurutan dari atas ke bawah  

---

## 📂 Dataset
Dataset putusan dapat diunduh dari repository ini:
- `dataset_putusan_denpasar.zip`

---

## 📄 Catatan
Proyek ini dibuat untuk keperluan akademik dan pembelajaran.  
Seluruh dataset berasal dari sumber publik dan diproses sesuai kebutuhan tugas.

---
