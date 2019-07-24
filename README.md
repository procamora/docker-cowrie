# docker-cowrie

Esta imagen de Cowrie usa el mismo Dockerfile con la excepción de que se ha modificado la salida de los logs a ficheros, en vez de usar la salida del sistema operativo

Se ha modificado la linea:

```bash
stdout=yes
```


por:


```bash
stdout=no
```
