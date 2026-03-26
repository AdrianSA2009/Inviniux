# Aplikasi Stok Gudang Elektronik

[](https://www.google.com/search?q=%5Bhttps://laravel.com%5D\(https://laravel.com\))
[](https://tailwindcss.com)
[](https://www.polibatam.ac.id/)

Aplikasi Stok Gudang Elektronik adalah sistem manajemen inventaris berbasis web yang dirancang untuk mengoptimalkan pengaturan dan pengawasan persediaan barang di gudang. Sistem ini memungkinkan pencatatan barang masuk dan keluar secara akurat serta menghasilkan laporan stok otomatis.

## 📋 Fitur Utama

### Admin Gudang

  * **Manajemen Data**: Mengelola kategori barang, data barang, dan data supplier.
  * **Transaksi**: Mencatat dan memanipulasi data barang masuk serta barang keluar.
  * **Pelaporan**: Mengunduh laporan stok dalam format Excel dan melihat riwayat transaksi.

### Manajer

  * **Monitoring**: Mengakses dashboard untuk memantau pergerakan stok melalui grafik.
  * **Laporan**: Melihat dan mengunduh laporan stok tanpa hak akses untuk mengubah data.

## 🛠️ Stack Teknologi

  * **Backend**: Laravel Framework.
  * **Frontend**: Tailwind CSS.
  * **Database**: MySQL.
  * **Tools**: Visual Studio Code, Git/GitHub, Laragon/XAMPP.

## 🚀 Metodologi Pengembangan (CDIO)

Proyek ini dikembangkan menggunakan kerangka kerja **CDIO**:

1.  **Conceive**: Identifikasi kebutuhan sistem dan penyusunan Rencana Pelaksanaan Proyek (RPP).
2.  **Design**: Perancangan UI (Wireframe), alur logika (Flowchart), dan skema basis data (ERD).
3.  **Implement**: Proses coding inti (frontend & backend) menggunakan Laravel.
4.  **Operate**: Pengujian fungsionalitas, perbaikan bug, dan finalisasi produk.

## 💻 Instalasi Lokal

Pastikan Anda sudah menginstal PHP (\>= 8.x), Composer, dan Node.js di perangkat Anda.

1.  **Clone repositori:**

    ```bash
    git clone https://github.com/username/stok-gudang-elektronik.git
    cd stok-gudang-elektronik
    ```

2.  **Instal dependensi:**

    ```bash
    composer install
    npm install && npm run dev
    ```

3.  **Konfigurasi Environment:**
    Salin file `.env.example` menjadi `.env` dan sesuaikan pengaturan database Anda.

    ```bash
    cp .env.example .env
    php artisan key:generate
    ```

4.  **Migrasi Database:**

    ```bash
    php artisan migrate --seed
    ```

5.  **Jalankan Server:**

    ```bash
    php artisan serve
    ```

## 👥 Tim Proyek

  * **Manajer Proyek**: Dwi Amalia Purnamasari, S.T., M.Cs.
  * **Developer**: Adrian Septiaji, Taqiyyah Aufaa Nabiilah, Cindo Maulina.

-----
