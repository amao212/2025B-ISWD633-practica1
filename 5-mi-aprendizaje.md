Aprendi nuevos comandos para usar en docker, me tomo un tiempo pero se pudo resolver
la primera practica
Primero tenemos el comando que nos ayuda a descargar imagenes "docker pull nombreimagen:version"
Luego tenemos el comando para los contenedores "docker create --name nombrecontenedor nombreimagen:version"
Tambien aprendimos como eliminar un contenedor que se este ejecutando
Luego casi al final descargamos jenkins y en la web nos pedia una contraseña, la cual se obtuvo con el siguiente comando
"docker exec -it cjenkins bash" y luego con cat se obtuvo la lectura de la siguiente dirección para obtener la contraseña "cat /var/jenkins_home/secrets/initialAdminPassword" y con esto se obtuvo la contraseña y pude acceder a jenkins
