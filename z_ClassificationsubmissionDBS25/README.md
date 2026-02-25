# Proyek Klasifikasi Gambar: Ayam, Anjing, Kucing, dan Gajah.
- **Nama:** Aprian Syahrani
- **Email:** apyansy@gmail.com
- **ID Dicoding:** aprian_syahrani_z6i4

## Deskripsi Proyek
Proyek ini bertujuan untuk membangun model untuk mengklasifikasikan gambar hewan ke dalam 4 kelas: ayam, anjing, kucing, dan gajah. Dataset yang digunakan diambil dari Kaggle (`alessiocorrado99/animals10`) dan dimodifikasi untuk hanya menggunakan 4 kelas tersebut.

## Sumber Dataset
- Dataset: https://www.kaggle.com/datasets/alessiocorrado99/animals10
- Jumlah gambar: 7114 (sebelum augmentasi)
- Kelas: ayam (2000), anjing (2000), kucing (1668), gajah (1446)

## Cara Menjalankan Notebook
1. Buka notebook `notebook.ipynb` di Google Colab.
2. Pastikan runtime menggunakan GPU (Runtime > Change runtime type > Hardware accelerator > GPU).
3. Jalankan semua cell secara berurutan.
4. Pastikan file `gambar_untuk_test_model.jpg` tersedia untuk inference (Cell 9).

## Hasil Akurasi
- Training Accuracy: 91.43%
- Validation Accuracy: 91.99%
- Test Accuracy: 96.56%