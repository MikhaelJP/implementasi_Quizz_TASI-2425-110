# PSI-24-04 Sistem Informasi Stok Obat Dinas Kesehatan Balige SISOB 

## Deskripsi Singkat
Pada saat ini internal Bidang Pelayanan dan Sumber Daya Kesehatan (PSDK) Dinas Kesehatan Balige dengan setiap Unit Pelaksana Tugas (UPT) Puskesmas di Toba masih belum menggunakan sistem informasi untuk memasukkan data obat, melihat stok obat, melakukan permintaan pengadaan stok obat, dan verifikasi permintaan pengadaan obat. Untuk melakukan kedua hal itu, staf Dinas Kesehatan masih menggunakan cara manual dengan cara mengecek langsung ke gudang dan memasukkan datanya ke microsoft excel. Untuk pengadaan obat, setiap UPT Puskesmas juga masih mengirimkan permintaan melalui pesan Whatsapp kepada staf PSDK atau mengantar langsung dokumennya ke kantor Dinas Kesehatan Balige. Oleh karena itu, dilakukan pengembangan sistem informasi stok obat Dinas Kesehatan Balige untuk bidang PSDK. Website ini berisi fitur-fitur untuk memasukkan data obat, melihat ketersediaan obat, permintaan pengadaan obat, dan verifikasi permintaan pengadaan obat.

## Fitur

Untuk mencapai tujuan tersebut kami menyediakan fitur fitur yang akan tersedia pada website SISOB yaitu :

- Fitur Kepala Dinas
  - Login
  - About Us
  - Data Obat: Memungkinkan Kepala Dinas untuk melihat pergerakan obat yang terjadi di Dinas Kesehatan.
  - Verifikasi Obat: Memverifikasi permintaan obat yang dilakukan oleh UPT Puskesmas yang ada di Toba ke Dinas Kesehatan.
  - Pencarian Obat: Membantu Kepala Dinas dalam mencari obat tertentu dalam sistem.

- Fitur PSDK
  - Register
  - Login
  - About Us
  - Registrasi Akun: Membuat akun Kepala Dinas dan setiap UPT Puskesmas.
  - Data Obat: Memungkinkan PSDK untuk memasukkan data obat yang ada di Dinas Kesehatan Toba ke dalam website.
  - Verifikasi Obat: Memverifikasi obat obat yang di request oleh UPT Puskesmas sebelum diverifikasi oleh Kepala Dinas.
  - Pencarian Obat: Puskesmas dapat mencari nama obat obat menggunakan fitur ini yang dapat kita lihat dalam sistem.

- Fitur Puskesmas
  - Login
  - About Us
  - Data Obat: Memungkinkan Puskesmas untuk memasukkan data data obat yang dimiliki gudang mereka ke dalam sistem.
  - Request Obat: Memungkinkan Puskesmas untuk melakukan permintaan obat ke PSDK untuk diadakan sesuai dengan kebutuhan.
  - Pencarian Obat: Puskesmas dapat mencari nama obat obat menggunakan fitur ini yang dapat kita lihat dalam sistem.

## Desain Arsitektur

Desain arsitektur yang terdapat pada sistem ini dapat dilihat pada ERD berikut:
![erd](https://github.com/proyek-mahasiswa/psi-2324ge-04-sisob/assets/89243930/da43a452-69a3-4e50-b2c7-310b7fc675dc)

## Database Design

Basisdata pada sistem ini terdiri dari beberapa tabel seperti:
**CDM**
![cdm](https://github.com/proyek-mahasiswa/psi-2324ge-04-sisob/assets/89243930/12bce8ce-a55d-43fc-a54c-27b365ddfd19)

**PDM**
![pdm](https://github.com/proyek-mahasiswa/psi-2324ge-04-sisob/assets/89243930/afc86a25-eb86-440e-a584-ad2460823f8e)

## Installation Guide

Langkah langkah instalasi yang dapat dilakukan untuk menjalankan Sistem Informasi Stok Obat Dinas Kesehatan Balige (SISOB) di perangkat anda yaitu

- Pastikan perangkat terhubung ke internet.
- Lakukan clone repositori SISOB dari github dan hubungkan ke direktori htdocs.
- Sediakan database kosong pada phpMyAdmin.
- Ubah file '.env'.
- Buka terminal pada direktori SISOB
- Instal semua dependensi laravel menggunakan perintah **composer install**
- Untuk menghasilkan kunci aplikasi laravel gunakan perintah **php artisan key:generate**
- Jalankan perintah migrasi untuk membuat skema basis data menggunakan perintah **php artisan migrate**
- Jika diperlukan, jalankan perintah **php artisan db:seed** untuk memasukkan data awal.
- Untuk menjalankan server gunakan perintah **php artisan serve**
- Buka pada web browser http://localhost:8000 atau alamat yang dihasilkan oleh printah diatas


### Minimum Hardware Requirements

Pesyaratan perangkat keras yang dibutuhkan dalam membangun sistem ini yaitu : 

- Prosesor : Intel Core i5-10300H
- Sistem Operasi : Windows 10 Home/Windows 11 Home
- Memori : 8 GB DDR4, 2933Hz
- Penyimpanan : 512 GB SSD M.2 PCIe NVMe

### Minimum Software Requirements

Perasyaratan perangkat lunak yang dibutuhkan dalam membangun sistem ini yaitu :

- Web Server : Apache
- Text Editor : Visual Studio Code
- Microsoft Office : Microsoft Word 2010
- Database : MariaDB, PhpMyAdmin
- Image Editor : Figma, Canva
- Diagram Editor : Bizagi Modeler, Star UML
- Framework : Laravel
- Testing Application : Postman


# Contributors
+ 12S21009 - Mikhael Janugrah Pakpahan (@GMikhaelJP)
+ 12S21011 - Aldi Jeremy Simamora (@aldijeremysimamora)
+ 12S21012 - Walker Valentinus Simanjuntak (@walkervalentinuss)
+ 12S21047 - Elshaday Prida Simamora (@elshadaysimamora)
+ 12S21056 - Endang Siregar (@endangsiregar)
