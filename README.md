<<<<<<< HEAD
# Klasifikasi Kualitas Beras Berbasis Pengolahan Citra Digital untuk Mendukung Ketahanan Pangan  Menggunakan SVM, KNN dan Naive Bayes

## Deskripsi

Proyek ini bertujuan untuk mengklasifikasikan kualitas beras berdasarkan citra digital guna mendukung ketahanan pangan (SDG 2: Zero Hunger)

Sistem dikembangkan menggunakan pendekatan **Pengolahan Citra Digital dan Machine Learning**, yaitu:

* **Preprocessing Citra** untuk membersihkan dan menyiapkan data
* **Ekstraksi Fitur Bentuk** untuk mengambil karakteristik beras
* **Machine Learning (SVM, KNN, Naive Bayes)** untuk klasifikasi

---

## Tujuan

* Mengklasifikasikan jenis beras secara otomatis dari citra
* Mengurangi subjektivitas penilaian manual
* Mengimplementasikan SVM, KNN, dan Naive Bayes
* Membandingkan performa ketiga algoritma

---

## Dataset

Dataset yang digunakan berasal dari Kaggle:

👉 https://www.kaggle.com/datasets/farahathaya/short-and-long-grain-rice-dataset-based-on-sni

Dataset berisi anotasi APD seperti:

* Long Grain
* Short Grain

---

## Metodologi

### 1. Preprocessing

* Konversi citra ke grayscale
* Gaussian blur untuk mengurangi noise
* Thresholding (Otsu) untuk segmentasi objek
* Morphological opening untuk membersihkan noise

### 2. Ekstraksi Fitur

* Deteksi kontur objek beras
* Mengambil kontur terbesar
* Ekstraksi fitur:
    * Area
    * Perimeter
    * Aspect Ratio

### 3. Klasifikasi

* SVM (Support Vector Machine)
* KNN (K-Nearest Neighbors, k=5)
* Naive Bayes (Gaussian)

### 4. Pipeline

1. Input citra
2. Preprocessing
3. Ekstraksi fitur
4. Klasifikasi

---

## Evaluasi

Evaluasi dilakukan menggunakan akurasi:


| Metode        | Akurasi |
|---------------|--------:|
| KNN           | 87.50%  |
| Naive Bayes   | 85.42%  |
| SVM           | 77.08%  |

---

## Hasil

* Klasifikasi jenis beras (Long Grain vs Short Grain)
* Perbandingan performa model
* Visualisasi akurasi dalam bentuk grafik

---

## Teknologi

* Python
* OpenCV
* NumPy
* Scikit-learn
* Matplotlib

---

## Anggota

* Mohammad Dimas Bahrul Ikhwani
* Fauzan Fathin Zaky

---

## Catatan

Dataset tidak diupload ke GitHub karena ukuran besar. Silakan download melalui link Kaggle.
=======
# UTS_Pengolahan-Citra
>>>>>>> 1be5f1ca450886af58a9b60c3c99e0cea6f32e39
