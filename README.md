
## Requirements
- Php 8.1

## Installation
git clone https://github.com/haroonalsharaby12/hospital-management.git
cd hospital-management
cp .env.example .env
composer install
php artisan key:generate
php artisan mi:f --seed
```
## Run The Project
- http://127.0.0.1:8000/login
 - [email] - admin@gmail.com
- [password] - 12345678
