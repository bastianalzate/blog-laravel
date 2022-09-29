# blog-laravel

## Correr proyecto


Recuerda tener instalada la version 8 de php, composer, npm y nodejs
## iniciar proyecto
```sh
git clone https://github.com/bastianalzate/blog-laravel.git
cd blog-laravel
Abre tu administrador de base de datos favorito y crea un base de datos llamada laravel
cp .env.example .env
composer install
php artisan migrate
npm i
npm run dev
npm run build
php artisan key:generate
php artisan serve
```

Dashboard y login

```sh
Revisa en la base de datos el email que se genero, colocala en el login y la contraseña es password
```

@Bastian Alzate


