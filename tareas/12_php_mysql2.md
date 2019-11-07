# PHP & MySQL

Se busca completar el stack LAMP con la instalación de MySQL y PHP en nuestro servidor, además se requiere crear un sitio, manteniendo el código fuente con GIT y se seguiran directivas de diseño HTML.

1. Instalar MySQL mediante el comando:
  `sudo apt-get install mysql-server mysql-client` Para la contraseña del usuario root utilice “T15J-sanjose”
2. Instale PHP 7 y el módulo para utilizar con apache. (en la versión 14.0 de ubuntu será necesario agregar el repositorio  ppa:ondrej/php)
  `sudo add-apt-repository ppa:ondrej/php`
  `sudo apt-get install php7.0 libapache2-mod-php7.0`
  `sudo apt-get install php7.0-mysql`
  (reinicie apache luego de realizado este paso.)
3. Cree un sitio en el servidor apache y dentro de dicho directorio agregue un archivo info.php conteniendo el código:
  `<?php phpinfo(); ?>`
4. Acceda al sitio e investigue el resultado obtenido.
5. Instale phpMyAdmin
  `sudo apt-get install phpmyadmin`


acceder al archivo donde se ubica el /var/www/Adminf/AdmInf-web
sudo touch info.php
sudo nano touch info.php <?php phpinfo(); ?>

investigar hay
/etc/apache2/sites-aviables
