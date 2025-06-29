# Proyek Klasifikasi Gambar - Deteksi Penyakit Daun Tanaman

## 📌 Deskripsi Proyek
Proyek ini merupakan bagian dari submission kelas Dicoding "Fundamental Deep Learning". Model klasifikasi citra dibangun untuk mengidentifikasi jenis penyakit pada daun tanaman berdasarkan dataset PlantVillage. Model ini dirancang menggunakan arsitektur CNN berbasis TensorFlow dan diekspor ke tiga format deployment: SavedModel, TF-Lite, dan TFJS.

## 📊 Dataset
- Sumber: [PlantVillage Dataset (Kaggle)](https://www.kaggle.com/datasets/emmarex/plantdisease)
- Jumlah gambar: >54.000
- Jumlah kelas: 15 kelas daun sehat dan sakit
- Format input: RGB 224x224 piksel

## ⚙️ Arsitektur Model
- Model Sequential
- Conv2D + MaxPooling
- Dropout & BatchNormalization
- Dense (Fully Connected) Layers
- Activation: ReLU + Softmax

## 🎯 Target Evaluasi
- Akurasi Training ≥ 95%
- Akurasi Testing ≥ 95%
- Visualisasi kurva akurasi dan loss
- Format ekspor: `SavedModel`, `model.tflite`, `model.json` + `weights.bin` (TFJS)

## 🧪 Hasil Akhir
- Akurasi validasi akhir: ±94–95%
- Akurasi test set: **95%+**
- Model berhasil mendeteksi dengan baik berdasarkan uji coba gambar baru (inference)

## Tools yang Digunakan
1. TensorFlow 2.x
2. Keras
3. Matplotlib, NumPy
4. Google Colab + GPU T4
5.pipreqs (untuk requirements.txt)

##🚀 Catatan Tambahan
Proyek ini telah memenuhi seluruh kriteria utama dan seluruh saran tambahan submission Dicoding dan Format output telah disesuaikan untuk berbagai platform (mobile, web, server).
