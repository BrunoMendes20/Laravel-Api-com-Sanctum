# Laravel CRUD API com Sanctum

API RESTful desenvolvida em Laravel com autenticação via token usando Sanctum.

## Tecnologias
- PHP
- Laravel
- Sanctum
- MySQL

## Instalação
git clone https://github.com/BrunoMendes20/Laravel-Api-com-Sanctum
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate
php artisan serve

## Autenticação
POST /api/login

## Endpoints
GET /api/clients  
GET /api/status
GET /api/clients/{id}
PUT /api/clients/{id}
POST /api/login
POST /api/logout
DELETE /api/clients/{id}

## Autor
Bruno Mendes
