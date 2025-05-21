
# 📝 Sentiment Analysis using SVM

## 📌 Project Title
**Sentiment Analysis using Support Vector Machine (SVM)**

## 👨‍💻 Author (Repo Asli)
[Jatin Warade](https://github.com/jatinwarade)

## 📁 Repository Asal
[GitHub Link](https://github.com/jatinwarade/Sentiment-analysis-using-SVM)

---

## 🧠 Project Overview
Proyek ini bertujuan untuk mengklasifikasikan teks menjadi *positif* atau *negatif* berdasarkan analisis sentimen. Model yang digunakan adalah **Support Vector Machine (SVM)** yang dilatih dengan data teks ulasan.

---

## ⚙️ Teknologi yang Digunakan
- Python
- `scikit-learn` — untuk SVM dan TF-IDF
- `pandas` — untuk manipulasi data
- `nltk` — untuk Natural Language Processing

---

## 📊 Alur Kerja

1. **Data Collection**
   - Dataset berisi teks ulasan + label sentimen (*positif/negatif*), biasanya dalam format CSV.

2. **Preprocessing**
   - Pembersihan teks (hapus angka, simbol, dll)
   - Tokenisasi
   - Stopword removal
   - Stemming (mengubah kata ke bentuk dasar)

3. **Feature Extraction**
   - Menggunakan **TF-IDF Vectorizer** untuk mengubah teks ke bentuk angka (numerik).

4. **Model Training**
   - Algoritma **SVM (Support Vector Machine)** dilatih dengan data latih.

5. **Evaluation**
   - Evaluasi akurasi model menggunakan data uji.
   - Metrik yang digunakan: confusion matrix, precision, recall, dan F1-score.

---

## ✅ Output
- Model mampu memprediksi apakah kalimat termasuk sentimen **positif** atau **negatif**.
- Hasil evaluasi ditampilkan di terminal saat script dijalankan.

---

## 🧪 Cara Menjalankan Proyek

```bash
# Clone repo
git clone https://github.com/jatinwarade/Sentiment-analysis-using-SVM.git
cd Sentiment-analysis-using-SVM

# Buat virtual environment
python -m venv venv

# Aktifkan venv
# Windows PowerShell
.env\Scripts\Activate.ps1

# Command Prompt
venv\Scriptsctivate

# Install package yang dibutuhkan
pip install scikit-learn pandas nltk

# Jalankan script
python svm_sentiment_analysis.py
```

---

## 📌 Catatan Tambahan
- Beberapa modul tambahan dari `nltk` perlu diunduh sebelum digunakan:

  ```python
  import nltk
  nltk.download('stopwords')
  nltk.download('punkt')
  ```

---

## ✍️ Report dibuat oleh:
**Azfa**  
(Me-review dan mendokumentasikan ulang dari repo asli sebagai latihan dokumentasi proyek.)
