# Eloquent Car Rental (Laravel)

Cardex is a comprehensive car rental platform designed to simplify the process of renting cars. This repository contains the code for the website and administration panel built using Laravel and Bootstrap respectively.

## Screenshots
![Cardex1](./imgs/cardex1.png)
![Cardex2](./imgs/cardex2.png)
![Cardex3](./imgs/cardex3.png)

## Features

### User-Facing Website

- User registration and authentication.
- Browse and search available cars.
- Filter cars by location, date, and other specifications.
- Make online reservations and manage bookings.
- View rental history and invoices.

### Administration Panel

- Secure login for administrators.
- Manage car listings, including creation, editing, and deletion.
- Track and manage car availability and reservations.

## Setup
1. Clone the repository:

```bash
   git clone https://github.com/Stucom-Pelai/MP0613_RA6RA7RA8_Eloquent-Car.git
```

2. Install Composer dependencies:

```bash
composer install
```

3. Copy the example enviroment file:

```bash
cp .env.example .env
```

4. Generate an application key

```bash
php artisan key:generate
```

5. Create a symbolic link from 'public/storage' to 'storage/app/public'

```bash
php artisan storage:link
```

6. Clear compiled view files

```bash
php artisan view:clear
```

7. Create mp0613_car database


8. Run migrations and seed the database

```bash
php artisan migrate:fresh --seed
```

9. Start the Laravel development server 

```bash
php artisan serve
```

10. You are all set
