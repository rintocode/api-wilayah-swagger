# API Wilayah Indonesia
API Wilayah Indonesia adalah project open source laravel untuk akses data Provinsi, Kabupaten, Kecamatan dan Kelurahan di Indonesia.
Project ini sudah disertai dengan Dokumentasi Api menggunakan Swagger.
## Requirement
- PHP 8.1
- MYSQL (untuk Database)
- Composer 2.1^
- Internet, karena menggunakan composer dan untuk mengunduh dependency yang diperlukan saat install
- Git (Optional) Untuk clone project
- Code Editor (Optional) Untuk edit konfigurasi .env (bisa pakai notepad, notepad++, vscode, sublime, atau nano, vim dll)

## Installation
Secara default, master data  Provinsi, Kabupaten, Kecamatan dan Kelurahan ada di folder `public/json` dengan format json.

- Untuk migrasi jalankan command :
```
php artisan migrate
```
- Untuk seeding data jalankan command :
```
php artisan db:seed --class=FromJsonSeeder
```
## Run Project
- Jalankan command :
```
php artisan serve
```
- Buka browser, akses http://127.0.0.1:8000
Done.

## Dokumentasi API
Master dari file dokumentasi yaml ada di folder `public/docs`.
Untuk membuka dokumentasi API, buka  http://127.0.0.1:8000/api/documentation

## Roadmap
- [x] Update data terbaru
- [x] Include kode pos
- [ ] Include latitude and longitude
- [ ] Include dasboard to manage data
