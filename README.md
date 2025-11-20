# ⚙️ Praktikum 8: PHP dan Database MySQL (CRUD Barang)

**Nama:** Zaid Al Anshary

**NIM:** 312410315

**Kelas:** TI 24A4

**Mata Kuliah:** Pemrograman Web

**Dosen Pengampu:** Agung Nugroho, S.Kom., M.Kom.

---

## 📚 Deskripsi Proyek

Repository ini berisi implementasi aplikasi CRUD (Create, Read, Update, Delete) sederhana untuk mengelola data barang, sesuai dengan panduan Praktikum 8.

Aplikasi ini menggunakan teknologi:
* **PHP** (sebagai bahasa *server-side*).
* **MySQLi** (untuk koneksi dan query database).
* **MySQL** (sebagai database server).

Fitur yang diimplementasikan meliputi:
1.  **Read:** Menampilkan semua data barang dalam bentuk tabel (`index.php`).
2.  **Create:** Menambah data barang baru, termasuk fitur *upload* gambar (`tambah.php`).
3.  **Update:** Mengubah data barang yang sudah ada (`ubah.php`).
4.  **Delete:** Menghapus data barang (`hapus.php`).

---

## 📂 Struktur File Proyek

| No | Nama File | Deskripsi |
|----|------------|-----------|
| 1 | **koneksi.php** | Script konfigurasi untuk menghubungkan PHP dengan Database MySQL (`latihan1`). |
| 2 | **index.php** | Halaman utama yang menampilkan daftar data barang (Fitur **Read**). |
| 3 | **tambah.php** | Form dan logika untuk menambah data barang baru (Fitur **Create**). |
| 4 | **ubah.php** | Form dan logika untuk mengedit/memperbarui data barang (Fitur **Update**). |
| 5 | **hapus.php** | Script untuk menghapus data barang berdasarkan ID (Fitur **Delete**). |
| 6 | **gambar/** | Folder tempat menyimpan file gambar yang diunggah. |

---

## 📸 Tampilan Program


### 1. Halaman Data Barang (index.php) - Fitur READ

<img width="1366" height="768" alt="Screenshot (271)" src="https://github.com/user-attachments/assets/26410932-979e-4b13-ae28-9c0ee4d05aca" />


### 2. Form Tambah Barang (tambah.php) - Fitur CREATE

<img width="1366" height="768" alt="Screenshot (272)" src="https://github.com/user-attachments/assets/35009cb4-c13e-4c2d-8abb-82749a3e572c" />

<img width="1366" height="768" alt="Screenshot (273)" src="https://github.com/user-attachments/assets/3b5e0c3a-ff4b-4645-bc61-39a07c4d4507" />


### 3. Form Ubah Barang (ubah.php) - Fitur UPDATE

<img width="1366" height="768" alt="Screenshot (274)" src="https://github.com/user-attachments/assets/127d1c17-24f2-4dcf-a38d-c9a637085a4a" />

### 4. Menampilkan tabel di Terminal

<img width="1366" height="768" alt="Screenshot (276)" src="https://github.com/user-attachments/assets/bd4786a1-bfcb-46ce-9b01-77b20db5c10b" />

### 5. Bagian di phpmyadmin

<img width="1366" height="768" alt="Screenshot (270)" src="https://github.com/user-attachments/assets/dcb60a7e-9bb7-4c86-9337-7a330fe5ea63" />



---

## ⚙️ Cara Menjalankan Program

1.  **Persiapan Database:** Pastikan modul **Apache** dan **MySQL** pada XAMPP sudah **Running**. Buat database **`latihan1`** dan tabel **`data_barang`** (seperti langkah di CMD).
2.  **Penempatan File:** Salin semua file PHP dan CSS ke dalam folder `C:\xampp\htdocs\lab8_php_database`.
3.  **Akses Program:** Buka browser dan akses alamat:
    ```
    http://localhost/lab8_php_database/
    ```
4.  Program siap diuji coba untuk fungsi Tambah, Ubah, dan Hapus.
