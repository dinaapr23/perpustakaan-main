
Tugas UAS Praktikum Pemrograman Web
Sistem Informasi Perpustakaan (E-Library)

Aplikasi ini adalah sebuah Sistem Informasi Perpustakaan (E-Library) berbasis web yang dikembangkan untuk memenuhi tugas akhir mata kuliah Praktikum Pemrograman Berbasis Web.
Fitur-Fitur Utama

    CRUD (Create, Read, Update, Delete): Pengelolaan data buku dan data anggota.

    Autentikasi: Sistem login dan logout untuk administrator.

    Validasi Form: Validasi pada sisi server (PHP) dan klien (JS).

    Desain Responsif: Tampilan yang dapat menyesuaikan dengan perangkat desktop dan mobile.

    Fitur Tambahan:

        Pencarian data buku dan anggota.

        Upload gambar untuk sampul buku.

Teknologi yang Digunakan

    Framework PHP: Laravel

    Framework CSS: Tailwind CSS

    Framework/Library JS: Native JavaScript (untuk validasi form)

Cara Instalasi

    Clone repositori ini:

    git clone https://github.com/dinaapr23/perpustakaan-main.git

    Masuk ke direktori proyek:

    cd nama-repo

    Instal dependencies PHP:

    composer install

    Salin file .env.example dan ubah namanya menjadi .env:

    cp .env.example .env

    Generate application key:

    php artisan key:generate

    Konfigurasi database di file .env.

    Jalankan migrations untuk membuat tabel:

    php artisan migrate

    Jalankan aplikasi:

    php artisan serve

Link Demo / Live Demo

    Link Demo: [Masukkan link demo aplikasi jika dihosting]

© 2025 Dina Aprillita
