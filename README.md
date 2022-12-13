# Sistema-de-Inventario
Es un sistema de inventario para una producción en masa 

Proceso de intalación de las herramientas necesarias para la prueba del Sistema de Inventario OAC

Esto es un sistema en pleno desarrollo, se esta trabajando con MVC

1-) Tener instalado apache2 (lampp o Xampp en caso de windows).

  a-) Enlace a la instalación de Xampp https://www.apachefriends.org/es/index.html
  
  b-) Enlace a la instalación de apache2 para linux https://www.digitalocean.com/community/tutorials/how-to-install-the-apache-web-server-on-ubuntu-20-04-es
  
  
2-) Tener instalado el Mysql

  a-) Si instalas Xampp ya viene con Mysql y phpmyadmin instalado.
  
  b-) Pasos para la instalación de Mysql en linux. https://chachocool.com/como-instalar-mysql-server-en-debian-11-bullseye/
  
 Ya con los recursos necesarios instalados procederemos a clonar y descargar los archivos.
 
 Si tienes Xammpp debes dirigirte 
 
    1-) Disco Local C:
    
    2-) La carpeta llamda Xampp
    
    2-) La Carpeta llamda Htdocs
    
    3-) Descomprimimos el archvivo en dicha carpeta.
  
  Iniciamos el navegador 
  
    1-) Colocamos en la URL "localhost/Canaima1.09"
 
 Y ya tendra el sistema con lo visual.
 
 Instalación en linux
    
    1-) Nos dirijimos a la la raiz.
    2-) Carpeta "var/www/html"
    3-) Y descomprimimos el archivo.
    4-) Iniciamos apache2.
 
 Iniciamos el navegador 
  
    1-) Colocamos en la URL "localhost/Canaima1.09"
 
 Y ya tendra el sistema con lo visual.
    
 Se mantiene en desarrollo los modulos de creación de usuario e inicio de sesión. Por lo que para ver las vistas de lo que seria los roles/perfiles se utiliza la URL
 de esta forma:
 
    1-) "localhost/Canaima1.09/home".
    2-) "localhost/Canaima1.09/tecnico".
    3-) "localhost/Canaima1.09/analista".
    4-) "localhost/Canaima1.09/presidencia".

Para que asi puedan visualizar las vistas creadar.


NOTA: Este es un sistema que de un inicio se utilizo programación estructurada, para darle un poco más de fortaleza se esta trasladando a MVC por lo que muchos modulos
anteriormente creados, se estan pasando a MVC.
