# laravel-generator

Este paquete genera Crontroller (con documentacion swagger), Model (con sus relaciones), Repository y Request, con un comamndo para agilizar el desarrolo de sus aplicaciones

## Instalación
1 - Instalar
```
composer require pipeosorio1/laravel-generator --dev
```
2- Publicar la configuración del paquete por defecto
```
php artisan vendor:publish --tag=generator
```

## Usage
```
php artisan make:generator {table_name}
php artisan make:module:generator {module_name} {table_name}
```