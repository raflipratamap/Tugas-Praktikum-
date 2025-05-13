# 🌟 Sentiment Analysis Project  

## 👤 Informasi Penulis  
- **Nama**: Rafli Pratama Ferdian  
- **NIM**: 12270501111 

## 📝 Deskripsi Proyek  

Proyek Sentiment Analysis menggunakan metode Support Vector Machine (SVM) untuk mengklasifikasikan sentimen teks dengan akurasi tinggi.  

## 🎯 Tujuan Proyek  

- Mengembangkan model Machine Learning untuk analisis sentimen  
- Mengklasifikasikan teks menjadi kategori positif atau negatif  
- Memberikan wawasan mendalam tentang opini dalam data tekstual  

## 🧠 Konsep Utama  

### Sentiment Analysis  
- Teknik NLP untuk menganalisis sentimen  
- Menentukan polaritas teks (positif/negatif)  
- Memahami nuansa emosional dalam komunikasi  

### Metode SVM  
- Algoritma Machine Learning supervisi  
- Membuat hyperplane pemisah antar kelas  
- Optimal untuk klasifikasi data linear  

## 🛠 Teknologi  

![Python](https://img.shields.io/badge/Python-3.8+-blue)  
![scikit-learn](https://img.shields.io/badge/scikit--learn-0.24+-green)  
![NLTK](https://img.shields.io/badge/NLTK-3.6+-red)  

- Python  
- Scikit-learn  
- NLTK  
- Pandas  
- NumPy  
- Matplotlib  

## 📊 Metodologi  

1. Pengumpulan Data  
2. Preprocessing Teks  
3. Vectorisasi (TF-IDF)  
4. Pelatihan Model SVM  
5. Evaluasi Performa  

## 🚀 Instalasi  
# Clone repository  
git clone https://github.com/username/sentiment-analysis.git  

# Buat environment virtual  
python -m venv venv  
source venv/bin/activate  # Linux/Mac  
venv\Scripts\activate    # Windows  

# Install dependencies  
pip install -r requirements.txt  

# Download NLTK data  
python -m nltk.downloader punkt stopwords

**📈 Contoh Penggunaan**
# Prediksi sentimen  
from model import predict_sentiment  

review = "Produk ini luar biasa!"  
sentiment = predict_sentiment(review)  
print(f"Sentimen: {sentiment}")

**📊 Performa Model**
Metrik	Skor
Akurasi	91%
Precision	91.5%
Recall	91.5%
F1-Score	91.5%



