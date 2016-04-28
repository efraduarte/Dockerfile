# Dockerfile
Dockerfile para la ejecución de un contenedor docker con phpmyadmin, aún se encuentra en estado build.

Forma de ejecución de Dockerfile
--tag: tag que le vamos a dar al nuestro contenedor
--file: ubicación de nuestro archivo Dockerfile

docker build --tag="misdocker/phpmyadmin" --file="/opt/docker_projects/Dockerfile/phpmyadmin/Dockerfile" .
