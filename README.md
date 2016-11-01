Docker compose para la base de datos de la materia de Bases de Datos 1 de la Facultad de Informática
====


* Setear variables de entorno `mv .env.example .env` (editarla si es necesario)
* Ejecutar `docker-compose up -d` dentro de la carpeta del proyecto para levantar los servicios.
* Acceder mediante web a `http://localhost:8080`.
* Acceder mediante línea de comando con `docker exec -it MySQL_BBDD1 bash` al contenedor de la base de datos.
* Para detener los contenedores, ejecutar `docker-compose stop`.
