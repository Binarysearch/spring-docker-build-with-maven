# spring-docker-build-with-maven
Ejemplo de proyecto de spring con dockerfile para hacer el build de la imagen con maven


## Para crear la imagen de docker: 
docker build --pull --rm -f "Dockerfile" -t springdockerbuildwithmaven:latest "."

## Para ejecutar el contenedor: 
docker run springdockerbuildwithmaven:latest
