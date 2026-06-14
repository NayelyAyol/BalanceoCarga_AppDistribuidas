<h1 align="center"> Balanceo de Carga </h1>

## Descripción

En esta práctica se implementó un entorno distribuido utilizando Docker Compose. Para ello, se crearon dos servidores web con Flask, dos bases de datos MySQL y un balanceador de carga con Nginx. Dentro del sistema es posible registrar y visualizar películas a través del formulario web. Las solicitudes realizadas por los usuarios son distribuidas entre los dos servidores mediante Nginx con un balanceo de carga por pesos. Además, las bases de datos fueron configuradas con replicación para mantener la información sincronizada entre ambos servidores.

## Tecnologías utilizadas

* Docker Desktop
* Docker Compose
* Python Flask
* MySQL
* phpMyAdmin
* Nginx
