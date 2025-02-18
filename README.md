# KhanzaWeb

KhanzaWeb adalah proyek berbasis Laravel yang dapat digunakan untuk membangun aplikasi web modern.

## Persyaratan Sistem
Pastikan Anda telah menginstal persyaratan berikut sebelum menjalankan proyek ini:
- PHP (>= 8.1)
- Composer
- MySQL atau database lain yang didukung Laravel
- Ekstensi PHP yang diperlukan: OpenSSL, PDO, Mbstring, Tokenizer, XML, Ctype, JSON

## Instalasi dan Konfigurasi
Ikuti langkah-langkah di bawah ini untuk menginstal dan menjalankan proyek ini:

### 1. Clone Repository
```bash
git clone https://github.com/pujamalca/KhanzaWeb.git
cd KhanzaWeb
```

### 2. Instal Dependensi
#### a. Install Dependensi PHP
```bash
composer install
```

### 3. Konfigurasi Lingkungan
Salin file konfigurasi contoh dan sesuaikan jika diperlukan:
```bash
cp .env.example .env
```

### 4. Generate Application Key
```bash
php artisan key:generate
```

### 5. Konfigurasi Database
Edit file `.env` dan sesuaikan konfigurasi database:
```ini
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=nama_database
DB_USERNAME=root
DB_PASSWORD=
```

Kemudian jalankan migrasi untuk membuat tabel-tabel database:
```bash
php artisan migrate
```

### 6. Menjalankan Aplikasi
Jalankan server lokal untuk mengakses aplikasi:
```bash
php artisan serve
```
Aplikasi sekarang dapat diakses di `http://localhost:8000`.

## Pengujian
Untuk menjalankan pengujian unit dan fitur, gunakan perintah berikut:
```bash
php artisan test
```

## Lisensi
Proyek ini berada di bawah lisensi MIT. Silakan lihat file `LICENSE` untuk detail lebih lanjut.

---
Semoga panduan ini membantu dalam menginstal dan menjalankan KhanzaWeb! 🚀

