# compoeser_ledge
Anything require for compooser to build get data set

.Package Laravel yang berisi data Provinsi, Kabupaten/Kota, dan Kecamatan/Desa di seluruh Indonesia.
composer require laravolt/indonesia
.Kemudian publish migration dan config yang disediakan oleh package ini:
php artisan vendor:publish --provider="Laravolt\Indonesia\ServiceProvider"
.Selanjutnya gunakan perintah dibawah ini untuk mengeksekusi migration dari package ini dan mengeksekusi seeder untuk mengisi data wilayah.
php artisan migrate
php artisan laravolt:indonesia:seed
.Setelah mengeksekusi perintah diatas, kita telah memiliki data-data yang kita perlukan.
