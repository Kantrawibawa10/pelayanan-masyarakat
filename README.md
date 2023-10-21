<p align="center">
    <a href="https://github.com/sandinur157" target="_blank"><img src="https://media.tenor.com/GfSX-u7VGM4AAAAC/coding.gif" width="400"></a>
</p>

## Tentang Aplikasi

Aplikasi <b>Pelayanan masyarakat</b> sederhana yang digunakan untuk masyarakat dalam pengajuan sebuah surat pengajuan kepada desa dalam membuat sebuah Kartu Keluarga, Kartu Tanda Penduduk, dll

## Instalasi
#### Via Git
```bash
git clone https://github.com/Kantrawibawa10/pelayanan-masyarakat.git
```

### Download ZIP
[[Link](https://github.com/Kantrawibawa10/pelayanan-masyarakat/archive/refs/heads/master.zip)]

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
DB_DATABASE=admin_billing
DB_USERNAME=root
DB_PASSWORD=
```
Opsional
```bash
APP_NAME=Laravel
APP_ENV=local
APP_KEY=base64:MzM8eIe2f/kz4AhdeBOn3EJoPUPbqANPVVSOuYleMnI=
APP_DEBUG=true
APP_URL=http://e-billing
```
Generate key
```bash
php artisan key:generate
```
Migrate database
```bash
php artisan migrate
```
Seeder table User, Pengaturan
```bash
php artisan db:seed
```
Menjalankan aplikasi
```bash
php artisan serve
```

## License

[MIT license](https://opensource.org/licenses/MIT)
