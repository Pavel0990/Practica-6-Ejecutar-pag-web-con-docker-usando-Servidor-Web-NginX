# Proyecto Nginx con Docker Compose

Este proyecto ejecuta un servidor web Nginx utilizando Docker Compose.

## Pasos para ejecutar

1. Clona este repositorio:
   ```sh
   git clone <URL_DEL_REPOSITORIO>
   cd nginx_project
   ```

2. Ejecuta el contenedor:
   ```sh
   docker compose up -d
   ```

3. Accede a [http://localhost:8080](http://localhost:8080) para ver la página de prueba.

## Estructura del proyecto
```
nginx_project/
│── docker-compose.yml
│── src/
│   └── index.html
│── README.md
│── .gitignore
```
