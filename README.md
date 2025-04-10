# Fundamentos de contenerización.
## Actividad 1.Servidor Web Simple con Nginx.
Paso 1. Construir la imagencon el mismo nombre que el repositorio conn la version 1.0.
```
sudo docker image build --tag 117fcproyecto1:1.0 .
```
Paso 2. Ejecutar el contenedor en el puerto 80.
```
sudo docker container run -d -p 80:80 --name 117fcproyecto1  117fcproyecto1:1.0

```

Paso 3. comprobacion:http//localhost
```
**desde navegador

http://localhost   

**desde consola

sudo docker container ls    

```

Paso 4.Se pide modificar el fichero index.html desde el contenedor.

```
*** Para entrar al contenedor

sudo docker exec -it 117fcproyecto1 bash

```

