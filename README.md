# compoeser_ledge
Anything require for compooser to build get data set

.Package Laravel yang berisi data Provinsi, Kabupaten/Kota, dan Kecamatan/Desa di seluruh Indonesia.<br>
composer require laravolt/indonesia<br>
.Kemudian publish migration dan config yang disediakan oleh package ini:<br>
php artisan vendor:publish --provider="Laravolt\Indonesia\ServiceProvider"<br>
.Selanjutnya gunakan perintah dibawah ini untuk mengeksekusi migration dari package ini dan mengeksekusi seeder untuk mengisi data wilayah.<br>
php artisan migrate<br>
php artisan laravolt:indonesia:seed<br>
.Setelah mengeksekusi perintah diatas, kita telah memiliki data-data yang kita perlukan.<br>
