# Inven BS

Aplikasi inventaris barang sekolah menggunakan Framework Laravel 10. Aplikasi ini cocok untuk digunakan untuk di sekolah.

Beberapa CRUD menggunakan modal dan AJAX untuk pengambilan data agar mengurangi penggunaan pindah halaman.

### Prasyarat

Berikut beberapa hal yang perlu diinstal terlebih dahulu:

-   Composer (https://getcomposer.org/)
-   PHP ^8.1
-   MySQL
-   XAMPP

Jika Anda menggunakan XAMPP, untuk PHP dan MySQL sudah menjadi 1 (bundle) di dalam aplikasi XAMPP

### Fitur

-   CRUD Data Barang
-   Import/export excel barang
-   Print barang (seluruh/individual)
-   CRUD Data BOS (Bantuan Operasional Sekolah)
-   CRUD Data Ruangan
-   CRUD Data Pengguna
-   Pengaturan Profil


### Langkah-langkah instalasi

-   Clone repository ini

```bash
$ https://github.com/riomaryono/project-kp.git
```

-   Install seluruh packages yang dibutuhkan

```bash
$ composer install
```

-   Siapkan database dan atur file .env sesuai dengan konfigurasi Anda

-   Masukan nama sekolah pada konfigurasi .env untuk menampilkan nama sekolah pada print barang. Berikan tanda kutip jika nama sekolah mengandung spasi

Contoh:

```
NAMA_SEKOLAH="SMK REFORMASI"
```

-   Jika sudah, migrate seluruh migrasi dan seeding data

```bash
$ php artisan migrate --seed
```

-   Jalankan local server

```
$ php artisan serve
```

-   User default aplikasi untuk login

Administrator

```
Email       : admin@mail.com
Password    : secret
```

Staff TU (Tata Usaha)

```
Email       : stafftu@mail.com
Password    : admin
```

### Dibuat dengan

-   [Laravel](https://laravel.com) - Web Framework
# project-kp
