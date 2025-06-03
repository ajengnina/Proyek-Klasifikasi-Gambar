# 🍽️ Klasifikasi Gambar Makanan dengan TensorFlow

Proyek ini membangun model klasifikasi gambar menggunakan dataset [Food-101](https://www.vision.ee.ethz.ch/datasets_extra/food-101/), dengan fokus pada 5 kelas makanan yang dipilih. Model yang telah dilatih kemudian dikonversi ke beberapa format deployment, yaitu TensorFlow Lite, TensorFlow.js, dan SavedModel.

---

## 📌 Deskripsi Proyek

- **Model:** Convolutional Neural Network (CNN) menggunakan TensorFlow/Keras.
- **Dataset:** Subset dari Food-101 yang mencakup 5 kelas makanan.
- **Pra-pemrosesan:** Resize gambar, normalisasi piksel, dan augmentasi data.
- **Pelatihan:** Model dilatih selama 20 epoch.
- **Evaluasi:** Mencapai akurasi validasi sekitar **68%**.
- **Output:** Model dikonversi ke tiga format deployment berbeda.

---

## 🔁 Format Model

| Format           | Keterangan                                                  |
|------------------|-------------------------------------------------------------|
| `SavedModel`     | Format default TensorFlow untuk produksi dan fine-tuning.   |
| `TensorFlow Lite`| Format ringan untuk deployment di mobile & embedded system. |
| `TensorFlow.js`  | Format untuk integrasi di aplikasi web berbasis JavaScript. |

---

## 🧪 Cara Menjalankan

1. Clone repositori ini atau buka file `.ipynb` di Jupyter Notebook.
2. Instal dependensi:
   ```bash
   pip install -r requirements.txt
3. Jalankan seluruh sel pada notebook untuk:
    - Melatih model CNN
    - Mengevaluasi performa model
    - Mengonversi model ke format TFLite, TF.js, dan SavedModel

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
