#  Sistem Informasi Perpustakaan

Project ini merupakan aplikasi web sederhana berbasis **Laravel** yang dibuat untuk implementasi konsep **MVC (Model View Controller)** pada framework PHP.

Aplikasi ini digunakan untuk mengelola data buku perpustakaan seperti menampilkan, menambah, mengubah, dan menghapus data buku.

---

##  Fitur Aplikasi

- Dashboard Perpustakaan
- Menampilkan daftar buku
- Menambahkan data buku
- Mengedit data buku
- Menghapus data buku
- Tampilan modern menggunakan Bootstrap 5

---

##  Teknologi yang Digunakan

- Laravel
- PHP
- MySQL
- Bootstrap 5
- Laragon

---

##  Konsep MVC

### Model
Menggunakan model `Buku` untuk mengambil dan mengelola data dari database.

### View
Menggunakan Blade Template Laravel untuk membuat tampilan halaman.

### Controller
Menggunakan `BukuController` untuk mengatur logika aplikasi dan proses CRUD.

---

##  Database

Database menggunakan MySQL dengan nama:

```bash
db_perpustakaan
```

File database:

```bash
db_perpustakaan.sql
```

---

##  Cara Menjalankan Project

### 1. Jalankan Laragon
Aktifkan:
- Apache
- MySQL

### 2. Import Database
Import file:

```bash
db_perpustakaan.sql
```

ke database MySQL.

### 3. Jalankan Laravel

Buka terminal pada folder project lalu jalankan:

```bash
php artisan serve
```

### 4. Buka Browser

```bash
http://127.0.0.1:8000/buku
```

---

##  Tampilan Aplikasi

Fitur utama:
- Dashboard
- Data Buku
- Tambah Buku
- Edit Buku
- Hapus Buku
- Detail Buku

---

##  Dibuat Oleh

**Fitri Ani**
2408107010022

Project tugas implementasi framework Laravel MVC.
