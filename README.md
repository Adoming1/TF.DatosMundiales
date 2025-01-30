## Installation

1- Importación de la BD:
Para la importación de la BD World se hace uso del asistente de importación Workbench. 
Los scripts que se importan son los proporcionados como material para la práctica:

world_city.sql 
world_country.sql
world_countrylanguage.sql

Abrimos MYSQL Workbench.
En el menú superior seleccionamos la pestaña Server >> Data Import:
Luego procedemos a analizar el contenido de las tablas 

Select * from world_city

Select * from world_country

Select * from world_countrylanguage

2- Conexión a MYSQL desde python

Requisitos: Conectarse desde Python a MYSQL, utilizando la librería: mysql-connector-python.
Es importante tener en cuenta para la conexión de Python y MYSQL, que en el proceso de instalación de MySQL el Authentication Method seleccionado sea Use Legacy Authentication Method, en caso de realizar la instalación con el método recomendado, al intentar realizar la conexión se arrojará el siguiente error de compatibilidad:
NotSupportedError: Authentication plugin 'caching_sha2_password' is not supported

    
