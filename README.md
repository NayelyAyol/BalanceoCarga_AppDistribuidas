<h1 align="center"> Balanceo de Carga </h1>

## Descripción

En esta práctica se implementó un entorno distribuido utilizando Docker Compose. Para ello, se crearon dos servidores web con Flask, dos bases de datos MySQL y un balanceador de carga con Nginx.

## Funcionalidad

El sistema permite registrar y visualizar películas a través de formularios web. Las solicitudes realizadas por los usuarios son distribuidas entre los dos servidores mediante Nginx utilizando un balanceo de carga por pesos. Además, las bases de datos fueron configuradas con replicación para mantener la información sincronizada entre ambos servidores.

## Tecnologías utilizadas

* Docker Desktop
* Docker Compose
* Python Flask
* MySQL
* phpMyAdmin
* Nginx

## Objetivo alcanzado

Con esta práctica se logró comprender y aplicar el concepto de balanceo de carga en aplicaciones distribuidas, así como reforzar el uso de contenedores y la replicación de bases de datos. También se evidenció cómo estas tecnologías contribuyen a mejorar la disponibilidad, el rendimiento y la confiabilidad de un sistema.
