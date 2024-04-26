# WEB GALLERY

## Tentang Website

Aplikasi Web Galery Ujikom yang dibuat sederhana

## Fitur

Untuk Fitur masih minim:
- sign up
- log in
- log out
- multiuser
- add poto
- add album
- edit profile
- add comment
- edit comment
- delete comment
- like
- dll

## Tampilan Website

![alt text](https://github.com/mayangmonika/mayang_gallery/blob/main/public/1.jpeg?raw=true)

![alt text](https://github.com/mayangmonika/mayang_gallery/blob/main/public/2.jpeg?raw=true)

![alt text](https://github.com/mayangmonika/mayang_gallery/blob/main/public/3.jpeg?raw=true)
## ERD, Relasi dan UML Use Case

- ERD

![alt text](https://github.com/mayangmonika/mayang_gallery/blob/main/public/4.jpeg?raw=true)

- Relasi

![RELASI](https://github.com/Wanzzy1/galeriwahdan2/assets/126433722/71728000-c1e8-4da6-817e-d300652ad245)

- UML

![UML](https://github.com/Wanzzy1/galeriwahdan2/assets/126433722/1b77e8dd-933c-4ac0-9413-0306769dd84b)

## Prasyaratan

- PHP 8.2.8 & Web Server (Apache, Lighttpd, atau Nginx)
- Database (MariaDB dengan v11.0.3 atau PostgreSQL)
- Web Browser (Firefox, Safari, Opera, Microsoft Edge dll)

## Instalasi
1. Clone Repository
```
https://github.com/Wanzzy1/galeriwahdan2
```

2. Install Composer
```
composer install
```
atau
```
composer update
```

3. Copy .Env
```
copy .env.example .env
```

4. Setting database di .env
```
DB_PORT=3306
DB_DATABASE=laravel_gallery
DB_USERNAME=root
DB_PASSWORD=
```

5. Generate key
```
php artisan key:generate
```

6. Jalankan migrate dan seeder
```
php artisan migrate --seed
```

7. Buat Storage Link
```
php artisan storage:link
```

8. Jalankan Serve
```
php artisan serve
```

