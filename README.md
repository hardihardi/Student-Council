## Instalasi

### Spesifikasi
- PHP ^8.1
- Laravel 10.x
- Database MariaDB

### Cara Install

1. Clone atau download source code
    - Para terminal, clone repo `git@github.com:hardihardi/Student-Council.git`
    - atau `git clone https://github.com/hardihardi/Student-Council.git`
    - Jika tidak menggunakan Git, silakan **Download Zip** dan *extract* pada direktori web server (misal: laragon/www atau xampp/htdocs)
2. `cd Student Council`
3. `composer install`
4. `cp .env.example .env`
    - Jika tidak menggunakan Git, bisa rename file `.env.example` menjadi `.env`
5. Pada terminal `php artisan key:generate`
6. Buat **database pada mysql** untuk aplikasi ini
7. **Setting database** pada file `.env`
8. `php artisan migrate --seed`
9. `php artisan serve`
10. Selesai
