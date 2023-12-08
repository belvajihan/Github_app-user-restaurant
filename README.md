## 💻 Panduan Instalasi Project

1. **Clone Repository**
```bash
git clone https://github.com/belvajihan/Belva.git
cd Belva
composer install
copy .env.example .env
```
2. **Buka ```.env``` lalu ubah baris berikut sesuaikan dengan databasemu yang ingin dipakai**
```
DB_PORT=3306
DB_DATABASE=app_kasir_restoran
DB_USERNAME=root
DB_PASSWORD=
```

3. **Migration & Seeder Database SQL** (pastikan internet nyala, untuk mengunduh gambar dari setiap menu)
```bash
php artisan migrate
php artisan db:seed
```

4. **Jalankan bash**
```bash
php artisan key:generate
```

5. **Jalankan website**
```bash
php artisan serve
```

5. **Akun Login**
```bash
Admin
username: admin
password: asd321 

Manager
username: manager 
password: asd321

Kasir
username: cashier
password: asd321 
```
