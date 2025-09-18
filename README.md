# Customer Personality Analysis

Proyek ini berfokus pada analisis data pelanggan dari sebuah kampanye marketing. Tujuan utama adalah memahami karakteristik pelanggan, pola pembelian, dan memberikan insight yang bisa membantu perusahaan dalam strategi pemasaran.

---

## Deskripsi Project
- Dataset: `marketing_campaign.csv` (data pelanggan dengan informasi demografi, pendapatan, status pernikahan, jumlah anak, dan pembelian produk).
- Tujuan: 
  - Membersihkan data (missing values, duplikat, outlier).
  - Membuat variabel baru (misalnya usia, jumlah anak).
  - Melakukan analisis deskriptif untuk memahami perilaku pelanggan.
  - Memberikan insight yang relevan untuk strategi marketing.

---

## Tools & Teknologi
- Python (Pandas, Numpy, Matplotlib, Seaborn)
- Jupyter Notebook / Google Colab

---

## Langkah Analisis
1. **Data Cleaning**
   - Mengisi nilai kosong pada kolom `Income` dengan rata-rata.
   - Menghapus data duplikat.
   - Menghapus outlier (contoh: umur > 80 tahun).

2. **Feature Engineering**
   - Membuat kolom baru `Age` dari `Year_Birth`.
   - Membuat kolom `children` dari `Kidhome` + `Teenhome`.

3. **Descriptive Analytics**
   - Distribusi umur pelanggan.
   - Distribusi pendapatan.
   - Status pernikahan pelanggan.
   - Distribusi jumlah anak.
   - Produk dengan jumlah pembelian tertinggi.

---

## Hasil & Insight
- Mayoritas pelanggan berada pada rentang usia produktif (< 60 tahun).
- Pendapatan pelanggan memiliki distribusi yang lebar, dengan sebagian besar berada di kelas menengah.
- Status pernikahan paling dominan adalah **Married**.
- Sebagian besar keluarga memiliki **1–2 anak**.
- Produk yang paling banyak dibeli adalah **Wine**, diikuti oleh **Meat Products** dan **Gold Products**.

---

## Referensi
- Dataset: *Marketing Campaign Data* (sumber asli dapat dicantumkan di sini).
- Dokumentasi Pandas, Matplotlib, Seaborn.

---


