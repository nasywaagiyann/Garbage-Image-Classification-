
# Proyek Klasifikasi Gambar: Garbage Dataset

## Deskripsi Proyek
Proyek ini bertujuan untuk membangun model deep learning untuk mengklasifikasikan gambar sampah ke dalam kategori yang sesuai. Dataset yang digunakan adalah "Garbage Dataset", yang berisi berbagai jenis sampah seperti plastik, kaca, logam, dll.

## Dataset
Dataset terdiri dari gambar-gambar berbagai jenis sampah yang telah diklasifikasikan ke dalam beberapa kategori. Data diproses menggunakan teknik augmentasi untuk meningkatkan performa model.

## Arsitektur Model
Model deep learning yang digunakan dalam proyek ini melibatkan:
- Transfer Learning dengan arsitektur pre-trained ResNet101V2 
- Penyesuaian layer output sesuai dengan jumlah kelas.
- Penggunaan teknik Regularization seperti Dropout dan Batch Normalization.
- Optimizer: AdamW

## Cara Menjalankan
1. Pastikan semua requirements telah terinstall.
2. Jalankan notebook `Proyek_Klasifikasi_Gambar_Template_Submission_Akhir.ipynb` secara berurutan.
3. Pastikan dataset tersedia dan path dataset telah disesuaikan.

## Hasil Evaluasi
Model dievaluasi menggunakan:
- Akurasi
- Confusion Matrix
- Classification Report (precision, recall, f1-score)



