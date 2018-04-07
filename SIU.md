# Instrucciones
* ```git clone https://github.com/SIU-Toba/js-docker.git```
* Bajar jasper server. Yo bajé la 6.4.2 de acá https://razaoinfo.dl.sourceforge.net/project/jasperserver/JasperServer/JasperReports%20Server%20Community%20Edition%206.4.2/TIB_js-jrs-cp_6.4.2_bin.zip
Hay que bajar el archivo ```TIB_js-jrs-cp_6.4.2_bin.zip```
* Copiar el archivo bajado a la carpeta ```resources```
* Instalar docker-compose https://docs.docker.com/compose/install/
* Ejecutar
```bash
docker-compose build
docker-compose up
```
* Si no hubo errores se debe poder acceder a jasper en la siguiente url: ```http://localhost:8080/jasperserver``` con usuario: ```jasperadmin``` y password: ```jasperadmin```. El primer request tarda muuuuuuuucho.

* la API Rest está en ```http://localhost:8080/jasperserver/rest``` 
* Lo que sigue es probar el cliente PHP https://github.com/Jaspersoft/jrs-rest-php-client
