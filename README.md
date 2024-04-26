<p align="center">
    <a href="https://github.com/Yukodesuwwa" target="_blank"><img src="https://github.com/Yukodesuwwa/ujikom/blob/main/kasir.png" width="120"></a>
</p>

## Tentang Aplikasi

Aplikasi Dikasir adalah aplikasi yang digunakan untuk mengelola transaksi pada sebuah toko atau oleh kasir. Aplikasi ini dibuat menggunakan Laravel v10.* dan minimal PHP v8.2 jadi apabila pada saat proses instalasi atau penggunaan terdapat error atau bug kemungkinan karena versi dari PHP yang tidak support, Aplikasi Ini Hanya Untuk Tugas Uji KOmpetensi Semata

### Beberapa Fitur yang tersedia:
- Manajemen Kategori Produk
- Manajemen Produk
  - Laporan Stok Barang
- Manajemen Member atau Anggota
  - Diskon Member 
- Transaksi 
- Diskon 
  - Diskon Member
  - Diskon Barang
- Laporan Stok Barang & Laporan Transaksi
  - Bulanan
  - Harian
  - Custom Tanggal
- Manajemen User dan Profil
- User (Administrator, Kasir)

### Setup Aplikasi
Jalankan perintah 
```bash
composer update
```
atau:
```bash
composer install
```
Copy file .env dari .env.example
```bash
cp .env.example .env
```
Konfigurasi file .env
```bash
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=example_app
DB_USERNAME=root
DB_PASSWORD=
```
Opsional
```bash
APP_NAME=Laravel
APP_ENV=local
APP_KEY=base64:7ny8i06U6BGjRyeIDxeiJ1Oz3+SLjK3QIDaeesQdqWo=
APP_DEBUG=true
APP_URL=http://localhost
```
Generate key
```bash
php artisan key:generate
```
Database

Import sql dari file sql yang sudah tersedia

Menjalankan aplikasi
```bash
php artisan serve
```
