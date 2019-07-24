# docker-cowrie

Esta imagen de Cowrie 1.5.1 usa el mismo Dockerfile con la excepción de que se ha modificado la salida de los logs a ficheros, en vez de usar la salida del sistema operativo

Se ha modificado la linea:

```bash
ENV STDOUT=yes
```


por:


```bash
ENV STDOUT=no
```


La url del contenedor oficial es: https://hub.docker.com/r/cowrie/cowrie/
