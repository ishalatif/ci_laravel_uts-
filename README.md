<h1>LaraStarter</h1>
LaraStarter is Laravel v10 starter template with AdminLTE 3 and Bootstrap 5.

<!-- Ganti path di bawah ini dengan nama folder dan nama file gambar yang kamu upload -->
<!-- Misal, kamu simpan di: screenshots/dashboard1.png -->
<!-- Contoh URL raw (pastikan branch = main) -->
<p align="center">
  <img src="https://raw.githubusercontent.com/muhazmi/lara-starter/main/screenshots/dashboard1.png" width="800" />
</p>
<p align="center">
  <img src="https://raw.githubusercontent.com/muhazmi/lara-starter/main/screenshots/dashboard2.png" width="800" />
</p>
<p align="center">
  <img src="https://raw.githubusercontent.com/muhazmi/lara-starter/main/screenshots/dashboard3.png" width="800" />
</p>
<p align="center">
  <img src="https://raw.githubusercontent.com/muhazmi/lara-starter/main/screenshots/dashboard4.png" width="800" />
</p>
<p align="center">
  <img src="https://raw.githubusercontent.com/muhazmi/lara-starter/main/screenshots/dashboard5.png" width="800" />
</p>
<p align="center">
  <img src="https://raw.githubusercontent.com/muhazmi/lara-starter/main/screenshots/dashboard6.png" width="800" />
</p>

---

## Features
- Laravel Breeze (Blade)
- Spatie Permission v6 with multi role
- Indonesian Region by Laravolt include: Province, City, District, Village
- Dashboard Admin: CRUD Post, Category, Tag, User, Navigation, Permission, Role
- Dashboard Author: CRUD Post, Edit Profile

### Layout
Frontend: Bootstrap 5, Backend: AdminLTE 3

### Packages
- Yajra Datatable
- SweetAlert
- Select2
- Bootstrap Datepicker
- Fontawesome 6

> You can see all packages used in this repo from the `public/assets` folder and `composer.json` file.  
> However, not all are actively used, so check `layouts/app.blade.php` and `layouts/script.blade.php` for what's currently in use.

---

## How to Install
Make sure you're connected to the internet and have PHP 8.1+ installed.

```bash
composer install
cp .env.example .env
php artisan migrate
php artisan db:seed
