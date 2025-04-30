# 🌱 Klasifikasi Gambar Daun Tanaman - PlantVillage Dataset

## 🎯 Objective
Membangun sebuah model klasifikasi berbasis **Convolutional Neural Network (CNN)** yang mampu membedakan antara daun tanaman yang sehat dan yang sakit, serta mengidentifikasi jenis penyakit yang menyerang tanaman tersebut.

Model yang dilatih kemudian diekspor dalam berbagai format—**SavedModel (TensorFlow)**, **TFLite**, dan **TensorFlow.js**—agar dapat digunakan di berbagai platform seperti web dan perangkat mobile.

---

## 📂 Sumber Dataset
Dataset diambil dari Kaggle:
🔗 [PlantVillage Dataset oleh Mohit Singh](https://www.kaggle.com/datasets/mohitsingh1804/plantvillage)

---

## 🗂 Struktur File
- `Submission_Klasifikasi_Gambar_PlantVillage.ipynb`  
  Notebook utama untuk pelatihan dan ekspor model klasifikasi.

- `saved_model/`  
  Model dalam format TensorFlow SavedModel (untuk backend/development).

- `tfjs_model/`  
  Model dalam format TensorFlow.js (untuk aplikasi web).

- `tflite/`  
  Model dalam format TensorFlow Lite (untuk aplikasi mobile).

- `requirements.txt`  
  Daftar pustaka yang dibutuhkan.

- `README.md`  
  Dokumentasi proyek ini.

---

## ⚙️ Cara Menjalankan

### 1. Instalasi Dependensi
```bash
pip install -r requirements.txt
