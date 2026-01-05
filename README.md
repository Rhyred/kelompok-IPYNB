# 📊 Analisis Data Diabetes Melitus (Jawa Barat)

Selamat datang di repository Tugas Kelompok Pemograman Dasar. Proyek ini bertujuan untuk membedah dataset jumlah penderita Diabetes Melitus (DM) di Provinsi Jawa Barat (Open Data Jabar) menggunakan Python.

Repository ini mencakup seluruh tahapan analisis, mulai dari validasi data mentah hingga visualisasi trend dan penarikan kesimpulan.

---

## 📂 Struktur Proyek

Kami membagi analisis ini menjadi 4 modul utama:

### **A. Data Loading & Validation**

* **Fokus:** Memastikan data terbaca dengan benar.
* **Aktivitas:** Load CSV, Cek `head()`/`tail()`, cek tipe data (`.info()`), dan statistik deskriptif (`.describe()`).

### **B. Filtering & Sorting**

* **Fokus:** Mengiris (*slicing*) data untuk mencari informasi spesifik.
* **Aktivitas:**
  * Filter data khusus tahun 2019.
  * Mencari daerah "Zona Merah" (>100.000 kasus).
  * Ranking Top 10 Kabupaten/Kota dengan kasus tertinggi.

### **C. Aggregation & Transformation**

* **Fokus:** Statistik mendalam dan *Feature Engineering*.
* **Aktivitas:**
  * Menghitung total penderita per tahun & rata-rata per kota.
  * **Kategorisasi Otomatis:** Membuat label `Rendah`, `Sedang`, `Tinggi` berdasarkan jumlah kasus.
  * Menghitung persentase kontribusi tiap kota terhadap total tahunan.

### **D. Visualization & Analysis**

* **Fokus:** Menerjemahkan angka menjadi grafik bercerita.
* **Output Grafik:**
  * 📊 Bar Chart (Sebaran Kasus).
  * 📈 Line Chart (Trend Tahunan).
  * 🥧 Pie Chart (Proporsi Kategori).

---

## 💡 Insight & Kesimpulan Analisis

Berdasarkan hasil pengolahan data dan visualisasi (Soal No. 25), berikut adalah temuan utama kami:

### 1. 🏆 Wilayah dengan Kasus Tertinggi

* **Hotspot:** **Kabupaten Karawang, Kabupaten Bogor, dan Kabupaten Bekasi**.
* **Analisis:** Wilayah-wilayah ini konsisten berada di peringkat teratas. Terlihat korelasi kuat antara **jumlah penduduk** (padat) dengan tingginya angka penderita DM.

### 2. 📈 Tren: Naik atau Turun?

* **Status:** **Cenderung MENINGKAT.**
* **Analisis:** Grafik garis (*Line Chart*) menunjukkan kurva yang terus menanjak dari tahun ke tahun. Ini mengindikasikan bahwa laju penambahan pasien baru lebih cepat dibandingkan penanganan/penurunan kasus, kemungkinan didorong oleh faktor gaya hidup dan demografi.

### 3. ⚠️ Sebaran Tingkat Keparahan

* **Dominasi:** Kategori **"Sedang"** dan **"Tinggi"**.
* **Analisis:** Mayoritas daerah di Jawa Barat sudah berada di level waspada. Daerah dengan status "Rendah" sangat sedikit. Ini menunjukkan Diabetes Melitus adalah masalah kesehatan yang merata, bukan kasuistik lokal semata.

---

## 🛠️ Tech Stack

Project ini dibangun menggunakan:

* **Python 3.x**
* **Pandas** (Data Manipulation)
* **Matplotlib** (Data Visualization)

## 🚀 Cara Menjalankan (How to Run)

1. **Clone Repository:**
   ```bash
   git clone [https://github.com/username-kalian/nama-repo.git](https://github.com/username-kalian/nama-repo.git)
   ```
2. **Pastikan Dependencies Terinstall:**
   ```bash
   pip install pandas matplotlib
   ```
3. **Siapkan Dataset:**
   Pastikan file `dinkes-od_17448_jml_penderita_diabetes_melitus_brdsrkn_kabupatenko_v2_data.csv` ada di folder yang sama.
4. **Jalankan Notebook:**
   Buka file `.ipynb` utama dan jalankan semua cell (`Run All`).

---

**Kelompok Analisis Data**

* **Mochammad Sayyid Ath-Thariq (NIM 152024195)** - Bagian A
* **Robi Rizki Permana (NIM 152024141)** - Bagian B & C
* ****Moch Riezky Dwi Kuswanto** (NIM 152024133)** - Bagian D

*Project Tugas Kelompok - Analisis Data & Visualisasi Pemograman Dasar*
