# Plantila postgrest y pg-admin para docker

## Para ejecutar

- Desde la terminal ubica el directorio del archivo
- Ejecuta el siguiente comando:
  - docker-compose up y espera que descargue todo
- Abre docker desktop para monitoriar los servcios

## Establecer la conexion entre postgres y pg admin

- Entra la url **http://localhost/browser/**
- El user es **admin@admin.com** el password es: **admin** y en idioma elegimos español
- En la parte izquierda superior le damos clik derecho y le damos registrar y luego servidor.
- En el campo name pone el **nombre** que quieran
- Luego selecionamos la viñeta siguiente que dice **Conecction** y llenamos los campos con los siguientes datos:
  - Host name/address = postgres
  - Port = 5432
  - Maintenance database = postgres
  - Username = admin
  - Password = admin
