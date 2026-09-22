# CineDocker

# CÓMO INSTALAR
## Instalamos Docker Desktop y abrimos un container Nginx
### Se recomienda usar el puerto 8080. Si el puerto 8080 está ocupado, usamos el 8081.

### En la consola de Windows:

````bash
docker run -d -p 8081:80 nginx
````

## Colocamos el reopositorio en:
### usr/share/nginx, puedes acceder a ella desde terminal con:
```bash
cd usr
cd share
cd nginx
```

## Borramos la carpeta HTML y renombramos la carpeta del repositorio a 'html':
```bash
mv CinePractica html
```
