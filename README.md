#Spek
Laravel Versi 9.0
PHP Versi 8.0.2
MySQL Versi 10.4.22
Bootstrap Versi 5.2.1
Tailwindcss: 3.2.4
Node JS Versi 18.15.0


Installasi SADARI dari GitHub

Buka halaman GitHub repository dari project SADARI.
Klik tombol "Code" yang terdapat di sebelah kanan atas, kemudian pilih "Download ZIP" atau salin link HTTPS yang terdapat di bawahnya.
Jika Anda memilih "Download ZIP", ekstrak file yang telah diunduh ke dalam folder lokal komputer Anda. Jika Anda memilih salin link HTTPS, buka terminal dan jalankan perintah git clone <link HTTPS> untuk mengunduh repository ke dalam folder lokal.

Buka terminal dan pindah ke direktori tempat file project diunduh atau dikloning dengan perintah cd <nama_folder>.

Jika project menggunakan dependensi, pastikan Anda telah menginstal dependensi-dependensi tersebut dengan menjalankan perintah npm install atau composer install di terminal.

Salin file .env.example dengan perintah cp .env.example .env (untuk Mac dan Linux) atau copy .env.example .env (untuk Windows).

Buka file .env dan atur pengaturan database sesuai dengan konfigurasi database yang dimiliki.

Jika database belum dibuat, buatlah database baru di server Anda.
Jalankan perintah php artisan migrate untuk menjalankan migration dan membuat tabel-tabel di dalam database.
Jika ada data yang perlu dimasukkan ke dalam database, jalankan perintah php artisan db:seed untuk menjalankan seeder.
Jalankan perintah php artisan serve untuk menjalankan aplikasi di server lokal Anda.
