# 📂 Tugas Analisis Data (Bagian A)

Repository ini berisi **langkah awal** (Part A) dari proyek analisis data Diabetes Melitus di Jawa Barat. 

Fokus modul ini adalah **Data Ingestion** (baca data) dan **Exploratory Data Analysis (EDA)** dasar buat ngecek apakah data yang kita punya sudah "sehat" sebelum diolah lebih lanjut.

## 📝 Yang Dikerjain (Soal Dasar)

File ini (`tugas_bagian_a.ipynb`) isinya codingan buat:

* **Load Data:** Baca file CSV ke Python.
* **Cek Integritas:** Pake `.head()` sama `.tail()` buat mastiin data gak korup di awal atau akhir.
* **Cek Tipe Data:** Pake `.info()` buat liat ada yang *null* atau salah format gak.
* **Statistik Dasar:** Pake `.describe()` buat liat angka rata-rata, min, sama max sekilas.
* **Validasi Entitas:** * Mastiin tahun berapa aja yang kecatat.
    * Mastiin jumlah kota/kabupaten pas 27 (se-Jabar).
 
# 📂 Tugas Analisis Data (Bagian B)

Repository ini berisi solusi coding untuk **Bagian B (Filtering & Sorting)** dalam proyek analisis data Diabetes Melitus Jabar.

Di modul ini, kita fokus "mengiris" data (slicing) untuk menemukan insight spesifik, seperti mencari daerah zona merah atau melihat tren historis satu kota tertentu.

## 📝 Yang Dikerjain (Soal Pengolahan Data)

File ini (`tugas_bagian_b.ipynb`) menyelesaikan soal-soal berikut:

* **Filter Tahun:** Mengambil data spesifik tahun 2019 saja.
* **Filter Kasus Ekstrem:** Mencari kota/kabupaten yang kasusnya meledak (> 100.000 penderita).
* **Sorting (Pengurutan):** * Mengurutkan data dari penderita terbanyak ke paling sedikit.
    * *Multi-level sorting*: Urut berdasarkan tahun dulu, baru berdasarkan jumlah penderita (biar ranking tiap tahun kelihatan jelas).
* **Top 10 Ranking:** Menampilkan 10 kota dengan kasus tertinggi khusus di tahun 2019.
* **Regional History:** Menampilkan riwayat data lengkap untuk satu daerah spesifik (contoh: Kabupaten Bogor) dari tahun ke tahun.

## 🛠️ Tools
* **Python**
* **Pandas**

## 🏃 Cara Run
1.  Taro file `.csv` dataset di sebelah file script ini.
2.  Buka di VS Code / Jupyter.
3.  Gas **Run All**.

---
*Dibuat buat Tugas Kelompok Bagian A.*
