# Analisis Preprocessing Ulasan E-commerce

**Nama:** [ISI NAMA LENGKAP]  
**NIM:** [ISI NIM]  

## Deskripsi
Proyek analisis dataset ulasan produk e-commerce berbahasa Indonesia untuk melihat distribusi sentimen dan menerapkan preprocessing teks: case folding, cleaning, tokenisasi, stopword removal, dan stemming.

## Dataset
Sumber: https://huggingface.co/datasets/dipawidia/ecommerce-product-reviews-sentiment

Dataset berisi 11.606 ulasan menurut kartu dataset Hugging Face. Kolomnya adalah `review` (ulasan Bahasa Indonesia), `sentimen` (0=negatif, 1=positif), dan `translate` (terjemahan Inggris). Jumlah data dan distribusi aktual dihitung kembali oleh notebook saat dijalankan.

## File
- `Analisis_Preprocessing_Ulasan_Ecommerce.ipynb`: notebook utama.
- `requirements.txt`: dependensi Python.

## Cara menjalankan
1. Buka notebook di Google Colab atau Jupyter Notebook.
2. Isi nama dan NIM pada bagian awal notebook.
3. Jalankan semua sel dari atas ke bawah.
4. Pastikan koneksi internet aktif untuk mengambil dataset dan mengunduh resource NLTK.

## Hasil
Notebook menampilkan ukuran dataset, daftar kolom, tipe data, distribusi label sentimen dan grafik, hasil preprocessing, serta 10 contoh teks asli sebelum dan sesudah preprocessing. Notebook juga menyimpan hasil ke `ulasan_preprocessed.csv`.

## Catatan
README ini perlu diperbarui setelah repository dibuat dengan URL repository GitHub yang sebenarnya. Jangan menuliskan URL repository palsu.
