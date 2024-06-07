# API Company

API en Laravel utilizando autenticación Sanctum
- <b>PHP 8.1 </b>
- 2 CRUD, empleados y departamentos
- Se usa un  <b>Factory</b> para insertar registros en las tablas, ejecutándolo desde el <b>Seeder</b>
- Se utiliza <b>Validator</b> para validaro los input de la solicitud
- Se habilita para consumir con cliente web

Instalación:

1) Crear una base de datos mysql

2) Clonar o descargar el proyecto en el directorio de tu servidor web

3) Acceder mediante terminal a la carpeta del proyecto

4) Ejecutar:  <b>Composer install</b>

5) Crear el archivo .env con los comandos: <b> cp .env.example .env</b>

6) Generar la API key ejecutando: <b> php artisan key:generate </b>

7) En el archivo .env colocar el nombre de la base de datos

8) Para ejecutar las migraciones y seeder: <b>php artisan migrate --seed</b>

## Columnas de la tabla departamentos
- id 
- name

## Columnas de la tabla empleados
- id 
- name 
- email
- phone
- department_id


## Video de explicación

Si quieres ver el video en donde se realiza esta API paso a paso [te comparto el siguiente enlace](https://youtu.be/fsiPXKzcH2M)
"# Company" 
