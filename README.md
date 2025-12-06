# 📚 Praktikum RPL - Django: Manajemen Data Mahasiswa

[![Django Version](https://img.shields.io/badge/Django-4.x.x-blue?style=for-the-badge&logo=django)](https://www.djangoproject.com/)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)

## 🌟 Deskripsi Proyek

Proyek ini adalah implementasi sistem sederhana untuk manajemen data mahasiswa, dibuat sebagai bagian dari tugas atau praktik mata kuliah **Rekayasa Perangkat Lunak (RPL)**. Aplikasi ini dikembangkan menggunakan *framework* web **Django** (Python).

### Fitur Utama

* **CRUD** (Create, Read, Update, Delete) data Mahasiswa.
* **Daftar Mahasiswa:** Menampilkan NIM, Nama, dan Program Studi.
* **Tambah Mahasiswa:** Form untuk memasukkan data mahasiswa baru.
* **Aksi:** Tombol `Edit` dan `Hapus` untuk memodifikasi atau menghapus data yang sudah ada.
* **Sistem Otentikasi** (Login) dasar (berdasarkan tampilan).

## 🚀 Teknologi yang Digunakan

* **Backend:** Python, Django
* **Database:** (Sebutkan database yang Anda gunakan, cth: SQLite, PostgreSQL, MySQL)
* **Frontend:** HTML, CSS, (Sebutkan jika ada *framework*/library JS, cth: Bootstrap)

## 🛠️ Cara Menjalankan Proyek

### Prasyarat

Pastikan Anda telah menginstal:

* Python (Versi yang disarankan: 3.x)
* pip (Pengelola paket Python)

### Instalasi

1.  **Clone Repositori:**
    ```bash
    git clone [URL_REPOSITORI_ANDA]
    cd [NAMA_FOLDER_REPOSITORI]
    ```

2.  **Buat dan Aktifkan *Virtual Environment*:**
    ```bash
    # Linux/macOS
    python3 -m venv venv
    source venv/bin/activate
    
    # Windows
    python -m venv venv
    .\venv\Scripts\activate
    ```

3.  **Instal Dependensi:**
    ```bash
    pip install -r requirements.txt
    ```
    *(Pastikan Anda telah membuat file `requirements.txt`)*

4.  **Lakukan Migrasi Database:**
    ```bash
    python manage.py makemigrations
    python manage.py migrate
    ```

5.  **Jalankan Server Pengembangan (Development Server):**
    ```bash
    python manage.py runserver 127.0.0.1:8000
    ```

6.  Buka *browser* Anda dan kunjungi: `http://127.0.0.1:8000/mahasiswa/` (sesuai URL di gambar).

## 🤝 Kontribusi

Jika Anda ingin berkontribusi pada proyek ini, silakan buat *fork* repositori dan kirimkan *Pull Request*.

## 📝 Lisensi

Proyek ini dilisensikan di bawah Lisensi MIT. Lihat file [LICENSE](LICENSE) untuk detail lebih lanjut.
