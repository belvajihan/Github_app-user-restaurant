## 💻 Panduan Instalasi Project

1. **Clone Repository**
```bash
git clone https://github.com/belvajihan/Belva.git
cd Belva
composer install
copy .env.example rename->.env
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
php artisan config:cache
php artisan storage:link
php artisan route:clear
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

## 🧑 Pemilik

👤  <a href="https://www.instagram.com/arilanaskar_/"> **Ariel Anaskar**</a>
- Facebook : <a href="https://web.facebook.com/ariel.anaskar.95"> Ariel Anaskar</a>

## Contributing
Contributions, issues and feature requests di persilahkan.
Jangan ragu untuk memeriksa halaman masalah jika Anda ingin berkontribusi.
