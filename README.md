# Lab8Web
**Nama:** Naufal Azis
**NIM:** 312510133
**Kelas:** 1252A

## Tujuan
Memahami konsep dasar database, konsep CRUD dengan PHP, dan membuat program CRUD sederhana.

## 1. Menjalankan MySQL Server
Jalankan Apache dan MySQL lewat XAMPP Control Panel.

<img width="337" height="216" alt="image" src="https://github.com/user-attachments/assets/0150f745-a8b5-431e-8019-1ff7bad94851" />


## 2. Membuat Database dan Tabel
Buka `http://localhost/phpmyadmin/`, lalu jalankan `database.sql` (membuat database `latihan1`, tabel `data_barang`, dan 3 data awal).



## 3. koneksi.php
File untuk menghubungkan PHP ke MySQL memakai `mysqli_connect()`. Jika gagal, tampil pesan error dan program berhenti.



## 4. index.php (Read)
Mengambil semua data dengan `SELECT * FROM data_barang`, lalu menampilkannya dalam tabel menggunakan `mysqli_fetch_array()` di dalam `while`.


## 5. tambah.php (Create)
Form input barang (termasuk upload gambar). Data disimpan dengan `INSERT` lalu diarahkan kembali ke `index.php`.



## 6. ubah.php (Update)
Data diambil berdasarkan `id` dari URL, ditampilkan di form, lalu disimpan dengan `UPDATE`.


## 7. hapus.php (Delete)
Menghapus data berdasarkan `id` dengan `DELETE`, lalu kembali ke `index.php`.
