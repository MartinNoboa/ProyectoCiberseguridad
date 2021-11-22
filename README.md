# Proyecto Final Ciberseguridad Agosto - Diciembre 2021
Aplicación web para poner en práctica los estándares de seguridad para AW. Creado en Laravel, usando los framework Laravel Fortify and Bootstrap.


## Cómo usar este repositorio
Para poder usar este repositorio, necesitas tener instalado los siguientes programas:
[ ] Composer, o tu manejador de paquetes de **PHP** preferido.
[ ] Servido web local, recomendamos **XAMP**.
[ ] Aplicación de simulación de servidor **SMTP**, recomendamos `Mailtrap`. 



1. Descarga o clona este repositorio.
```shell
$ git clone https://github.com/MartinNoboa/ProyectoCiberseguridad.git
```

2. Instala las dependencias requeridas por Laravel.
```shell
composer install
```
En el repositorio, esta el archivo [composer.json](composer.json), donde se encuentran todas las depencias. 

3. Genera una `llave de aplicacion`.
```
# comando para crear una llave de aplicación en Laravel
php artisan key:generate
```
4. Crea tu base de datos en el DBMS de tu preferencia. Nosotros usamos `XAMPP`, por lo que la creamos en **MySQL** en **PHPMyAdmin**.

5. Copia el archivo `.env` del archivo base `.env.example`.
```shell
# Comando para copiar archivo .env 
cp .env.example .env
```

6. Configura el archivo `.env` desde tu editor de elección. Deberes configurar tu **base de datos** y tu servidor **SMTP**.

7. Corre las migraciones incluidas
```shell
# Comando para correr migraciones
php artisan migrate
```

8. Corre la aplicación de Laravel. Si estás usando XAMPP, recuerda encender Apache y MySQL
```shell
# Comando para correr aplicación de Laravel
php artisan serve
```

## Documentación
Si gustas entrar a más detalle acerca de la lógica del programa y los protocolos de seguridad, esta el archivo [Documentación.pdf](composer.json) que continen la documentación formal del proyecto. 


## Licencia
Este repositorio cuenta con una licencia [MIT](https://opensource.org/licenses/MIT).