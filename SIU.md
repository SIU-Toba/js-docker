# Instrucciones
* ```git clone https://github.com/SIU-Toba/js-docker.git```
* Bajar jasper server. Yo bajé la 6.3.0 de acá https://community.jaspersoft.com/project/jasperreports-server/releases#project_releases-old-2
Hay que bajar el archivo ```jasperreports-server-cp-6.3.0-bin.zip```
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
