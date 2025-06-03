# 🍽️ Klasifikasi Gambar Makanan dengan TensorFlow

Proyek ini membangun model klasifikasi gambar menggunakan dataset [Food-101](https://www.vision.ee.ethz.ch/datasets_extra/food-101/), dengan fokus pada 5 kelas makanan yang dipilih. Model yang telah dilatih kemudian dikonversi ke beberapa format deployment, yaitu TensorFlow Lite, TensorFlow.js, dan SavedModel.

---

## 📁 Struktur Folder
submission/
├───tfjs_model/ # Format TensorFlow.js
│ ├───group1-shard1of1.bin
│ └───model.json
├───tflite/ # Format TensorFlow Lite
│ ├───model.tflite
│ └───label.txt
├───saved_model/ # Format TensorFlow SavedModel
│ ├───saved_model.pb
│ └───variables/
├───notebook.ipynb # Notebook utama pelatihan & konversi model
├───README.md # Deskripsi proyek dan panduan
└───requirements.txt # Daftar dependensi Python


---

## 📌 Deskripsi Proyek

- **Model:** Klasifikasi gambar menggunakan Convolutional Neural Networks (CNN) dengan TensorFlow/Keras.
- **Dataset:** 5 kelas makanan yang dipilih dari Food-101.
- **Pra-pemrosesan:** Resize gambar, normalisasi, dan augmentasi.
- **Evaluasi:** Model dilatih selama 20 epoch dengan akurasi validasi sekitar 68%.
- **Output:** Format model yang dikonversi untuk berbagai kebutuhan deployment.

---

## 🔁 Format Model yang Dihasilkan

- `TFLite`: Untuk deployment di perangkat mobile atau embedded system.
- `TensorFlow.js`: Untuk digunakan di browser web.
- `SavedModel`: Format standar TensorFlow untuk produksi atau fine-tuning lanjutan.

---

## 🧪 Cara Menjalankan

1. Clone repositori ini atau buka file `notebook.ipynb` menggunakan Jupyter Notebook.
2. Instal seluruh dependensi:  
pip install -r requirements.txt

3. Jalankan seluruh sel dalam notebook untuk melatih dan mengonversi model.

---

## 🏷️ Label Kelas
0: apple_pie
1: beef_carpaccio
2: beef_tartare
3: caesar_salad
4: cheesecake


---

## 📦 Kebutuhan Sistem

Lihat file `requirements.txt` untuk detail lengkap dependensi Python.

---

## ✍️ Penulis

Ajeng Nina Riski  
Submission Dicoding — Klasifikasi Gambar dengan TensorFlow  
