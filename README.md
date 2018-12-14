# docker-baby-steps
Ejemplo simple de Dockerfile

# Pasos para construir esta imagen

docker build -t mi-primer-docker-file:1.0 .

# Pasos para correr esta imagen

 docker run -p 4000:80 mi-primer-docker-file:1.0
 
 # ¿Cómo pruebo que haya corrido?
 
 El aplicación debe estar disponible en el puerto 4000
 
 [![app](https://docs.docker.com/get-started/images/app-in-browser.png)
