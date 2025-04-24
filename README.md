# TASI-2425-110 website kuis 

## Deskripsi Singkat
Website ini adalah platform kuis interaktif yang dirancang untuk memberikan pengalaman belajar yang seru, fleksibel, dan cerdas. Dengan dukungan teknologi AI terbaru dari Gemini 1.5, website ini mampu secara otomatis menghasilkan soal-soal kuis yang bervariasi dan menantang, sehingga pengguna tidak hanya mengasah pengetahuan, tapi juga terbantu dalam proses belajar yang lebih mendalam.

Ada tiga jenis soal yang tersedia, yaitu:

- Multiple choice (pilihan ganda): Cocok untuk menguji pemahaman dasar dengan berbagai pilihan jawaban.

- Essay (uraian): Membantu pengguna mengembangkan pemikiran kritis dan kemampuan menjelaskan secara mendalam.

- True or false (benar atau salah): Ideal untuk pengujian cepat terhadap pemahaman konsep dasar.

Pengguna cukup masuk ke website, memilih topik atau membiarkan AI yang menentukan, lalu kuis akan secara otomatis dibuat dan siap dikerjakan. Setelah menyelesaikan kuis, pengguna bisa langsung melihat hasilnya—termasuk penilaian otomatis untuk soal pilihan ganda dan true or false, serta masukan cerdas untuk jawaban essay.

## Fitur

Untuk mencapai tujuan tersebut kami menyediakan fitur fitur yang akan tersedia pada website SISOB yaitu :

- Fitur Admin
  - Login
  - Create Quiz
  - Open Quiz
  - Generate Question 
  - Edit Question 

- Fitur User 
  - Register
  - Login
  - Start Quiz 
  - Leaderboard
  - See Question 


## Installation Guide

Langkah langkah instalasi yang dapat dilakukan untuk menjalankan Sistem Informasi Stok Obat Dinas Kesehatan Balige (SISOB) di perangkat anda yaitu

- Pastikan perangkat terhubung ke internet.
- Lakukan clone repositori Implementasi_Quizz_TASI_2425_110 dari github dan hubungkan ke direktori htdocs.
- Sediakan database kosong pada Firebase.
- Ubah file '.env'.
- Buka terminal pada direktori Implementasi_Quizz_TASI_2425_110
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
- Database : MariaDB, Firebase
- Image Editor : Figma, Canva
- Diagram Editor : Bizagi Modeler, Star UML
- Framework : Laravel
- Testing Application : Postman


# Contributors
+ 12S21009 - Mikhael Janugrah Pakpahan (@MikhaelJP)
+ 12S21002 - Marudut Budiman Tampubolon (@MarudutTMP)
+ 12S21056 - Endang Siregar (@endangsiregar)
