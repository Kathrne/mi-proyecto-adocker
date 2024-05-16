# Requerimientos:

• Se necesita un contenedor apache(httpd) con el nombre apacheServer.

• Debe de correr con el puerto 8080:80.

• Permitir que la imagen contenga soporte para php 8.2

• El archivo de inicio index.html debe de ser index.php

• Correr el siguiente código:
<?php 
 echo “<h1>Bienvenidos a mi implementación de Docker</h1>”
 echo “<p>Estoy iniciando el uso de contenedores en Docker<p>”
 $identificacion= “Mi nombre es ”
 $nombre=”William Morales”
 echo $identificacion.$nombre
?>