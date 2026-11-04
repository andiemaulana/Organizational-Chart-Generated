# Organizational-Chart-Generated

<img width="1589" height="760" alt="image" src="https://github.com/user-attachments/assets/08bf9fef-3f13-4bb2-bf5e-132aa85940dc" />

# Generator Bagan Organisasi

Aplikasi web berbasis klien (*client-side*) interaktif yang dirancang untuk memudahkan pembuatan struktur bagan organisasi secara otomatis, melakukan pratinjau secara langsung (*live preview*), dan mengekspor hasilnya langsung ke dalam format dokumen spreadsheet profesional (**Excel / .xlsx**).

## Fitur Utama

1. **Penyusunan Bagan Otomatis:** Cukup tentukan hubungan atasan-bawahan untuk setiap jabatan, dan sistem akan secara otomatis menyusun garis komando serta hierarki bagan organisasi.
2. **Garis Koordinasi (Opsional):** Mendukung penambahan hubungan fungsional atau koordinasi antar jabatan tanpa hubungan atasan-bawahan langsung (ditampilkan sebagai garis putus-putus).
3. **Identitas Dokumen & *Title Block*:** Personalisasi judul bagan, nama perusahaan/divisi, tanggal berlaku, serta nomor revisi yang terintegrasi rapi ke dalam blok judul dokumen.
4. **Kustomisasi Tema Warna:** Menyediakan beberapa pilihan templat warna siap pakai serta opsi kustomisasi warna manual untuk tingkat Pimpinan, Menengah, Pelaksana, hingga Garis Penghubung.
5. **Manajemen Data (JSON):** Memungkinkan Anda untuk menyimpan data jabatan ke dalam file berformat `.json`, memuatnya kembali, atau mereset ke data contoh (*sample data*) kapan saja.
6. **Ekspor Excel Profesional (.xlsx):** Menggunakan pustaka tersemat (**ExcelJS**) untuk merubah struktur bagan menjadi lembar kerja Excel yang bersih dan siap cetak.

---

## Struktur Proyek

* **`Generator-Bagan-Organisasi.html`**: Berkas tunggal utama yang mencakup antarmuka pengguna (HTML/CSS), logika interaktif antarmuka (JavaScript), serta pustaka pemrosesan spreadsheet (*ExcelJS*) yang tertanam secara mandiri di dalamnya.

---

## Cara Penggunaan

1. Buka file **`Generator-Bagan-Organisasi.html`** menggunakan peramban web modern (*Google Chrome, Mozilla Firefox, Microsoft Edge*, dll.).
2. **Langkah 01 (Identitas Dokumen):** Masukkan Judul Bagan, Nama Perusahaan/Divisi, Tanggal Berlaku, dan Nomor Revisi.
3. **Langkah 02 (Jabatan):** Tambahkan daftar jabatan, tentukan nama posisi/pejabat, serta pilih atasan masing-masing jabatan untuk membangun struktur hierarki.
4. **Langkah 03 (Garis Koordinasi - Opsional):** Tambahkan garis koordinasi fungsional jika diperlukan.
5. **Langkah 04 (Warna):** Pilih templat warna yang diinginkan atau sesuaikan warnanya secara manual.
6. **Langkah 05 (Data):** Anda dapat menyimpan data konfigurasi ke file `.json` untuk cadangan di masa mendatang.
7. Klik tombol **"Unduh Excel (.xlsx)"** di bagian kanan atas untuk mendapatkan hasil dokumen bagan organisasi dalam bentuk file Excel.

---

## Ketergantungan / Pustaka Pihak Ketiga

Proyek ini berjalan secara *standalone* di sisi peramban web dan mengandalkan sumber eksternal berikut (dimuat via CDN atau diembed langsung):
* **ExcelJS** (untuk pembuatan file `.xlsx`).
* **Google Fonts** (Bricolage Grotesque, IBM Plex Mono, IBM Plex Sans).

---
*Dikembangkan untuk otomatisasi pembuatan dokumen perusahaan secara cepat, efisien, dan akurat.*
