# 📊 Analisis Visualisasi Data Diabetes Melitus (Jawa Barat)

Repository ini berisi kode visualisasi dan analisis mendalam mengenai tren penyebaran Diabetes Melitus di Jawa Barat. Fokus modul ini adalah **Bagian D (Visualisasi Data)**, di mana angka-angka statistik diubah menjadi grafik yang bercerita.

## 🖼️ Fitur Visualisasi (Soal No. 20-24)
Kode dalam `tugas_visualisasi.ipynb` menghasilkan grafik-grafik berikut:

1.  **Bar Chart 2019:** Sebaran penderita di seluruh Kota/Kabupaten.
2.  **Line Chart:** Tren total penderita dari tahun ke tahun (Naik/Turun?).
3.  **Horizontal Bar (Top 10):** Ranking 10 wilayah dengan kasus tertinggi.
4.  **Pie Chart:** Proporsi kategori keparahan (`Rendah` vs `Sedang` vs `Tinggi`).
5.  **Multi-Year Comparison:** Perbandingan total kasus di 3 tahun terakhir.

---

## 💡 Analisis & Insight (Soal No. 25)

Berdasarkan grafik yang dihasilkan, berikut adalah kesimpulan dari data yang diolah:

### 1. 🏆 Siapa yang Tertinggi?
* **Wilayah:** **Kabupaten Karawang, Kabupaten Bogor, dan Kabupaten Bekasi**.
* **Penyebab:** Terlihat korelasi kuat antara jumlah penduduk dengan jumlah penderita. Wilayah-wilayah padat penduduk ini konsisten menempati peringkat atas di hampir setiap tahun.

### 2. 📈 Tren: Naik atau Turun?
* **Status:** **Cenderung MENINGKAT.**
* **Bukti:** Grafik garis (*Line Chart*) menunjukkan kurva yang terus menanjak setiap tahunnya. Hal ini mengindikasikan bahwa penambahan kasus baru lebih cepat daripada penyelesaian/penurunan kasus, kemungkinan didorong oleh perubahan gaya hidup dan peningkatan populasi.

### 3. ⚠️ Sebaran Kategori (Severity)
* **Dominasi:** Kategori **"Sedang"** dan **"Tinggi"**.
* **Artinya:** Mayoritas Kabupaten/Kota di Jawa Barat sudah berada di level waspada. Daerah dengan status "Rendah" jumlahnya sangat sedikit (minoritas). Ini menunjukkan Diabetes Melitus adalah masalah kesehatan yang merata di Jabar, bukan hanya masalah lokal satu-dua kota.

---

## 🛠️ Cara Menjalankan
1.  Pastikan library visualisasi terinstall:
    ```bash
    pip install pandas matplotlib
    ```
2.  Jalankan notebook `tugas_visualisasi.ipynb`.
3.  Grafik akan otomatis muncul di output cell.

---
*Project Tugas Kelompok - Analisis Data & Visualisasi*
