# TOPSIS - Sistem Penilaian Gizi (CodeIgniter)

Proyek ini merupakan implementasi metode **TOPSIS (Technique for Order Preference by Similarity to Ideal Solution)** menggunakan **CodeIgniter**, dengan tujuan melakukan **penilaian gizi** berdasarkan beberapa kriteria kemudian memberikan **grade** untuk setiap alternatif.

## ✨ Fitur Utama
- Input data **kriteria gizi** (benefit/cost & bobot)
- Input data **alternatif** (misalnya: makanan, menu, pasien, dll.)
- Perhitungan otomatis menggunakan metode TOPSIS:
  - Normalisasi
  - Pembobotan
  - Solusi ideal positif/negatif
  - Jarak alternatif
  - Nilai preferensi
- **Pemberian grade** (A, B, C, D) berdasarkan nilai preferensi
- Output berupa ranking gizi terbaik → terendah
- Dapat terintegrasi dengan database MySQL menggunakan model CI
