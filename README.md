Tugas Minggu 06  Halaman Registrasi

Deskripsi
Aplikasi sederhana berbasis PHP dan MySQL untuk melakukan registrasi pengguna.
Data yang diinputkan (nama, email, password) akan disimpan ke dalam database.

Fitur
- Form registrasi dengan input: nama, email, dan password
- Validasi input 
- Data tersimpan ke tabel `users` di database `db_registrasi`

Teknologi yang Digunakan
- PHP
- MySQL
- Laragon

Struktur File
- `config.php` : koneksi ke database
- `register.php` : halaman form registrasi dan proses simpan data
- `database.sql` : struktur database dan tabel

Struktur Tabel `users`
| Kolom      | Tipe         | Keterangan              |
|------------|--------------|-------------------------|
| id         | INT (PK, AI) | ID pengguna             |
| nama       | VARCHAR(100) | Nama lengkap            |
| email      | VARCHAR(100) | Email                   |
| password   | VARCHAR(255) | Password ter-hash       |
