# Laravel telepítési útmutató

## Előfeltételek

- PHP 8.1 vagy újabb verzió
- PHP csomagkezelő
- XAMPP
- MySQL

## 1. Telepítsd a composer-t

Töltsd le innen: https://getcomposer.org/download/

Ellenőrizd: composer -V

## 2. Laravel projekt létrehozása

Parancssorban: composer create-project laravel/laravel projektneve

Vagy ha telepíted globálisan a Laravel installert:

```bash
composer global require laravel/installer
laravel new projektneve
```

## 3. Fejlesztői szerver indítása

```bash
cd projektneve
```

Majd indítsd el a beépített szervert:

```bash
php artisan serve
```

Ha minden jól működik, a következő üzenetet látod:
Starting Laravel development server: http://127.0.0.1:8000

A futó projekt itt lesz elérhető:
http://127.0.0.1:8000

## 5. Környezeti beállítások (`.env` beállítása)

Másold le a példát:

```bash
cp .env.example .env
```

Generáld az alkalmazás kulcsot:

```bash
php artisan key:generate
```

Adatbázis beállítása a `.env` fájlban:

```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=adatbazis_nev
DB_USERNAME=felhasznalo
DB_PASSWORD=jelszo

```

## 6. Composer update & migrációk futtatása

```bash
composer install
php artisan migrate
```

---

Kész is!
