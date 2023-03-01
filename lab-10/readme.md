
## Laboratorio 


### Descripcion General

Este directorio contiene las instruciones para el primer ejercicio relacionado con el tema: Introduccion a las Apis


#### Actividades

*  Descargar repositorio
*  Levantar servidor de Mocks
*  Consumir los apis de ejemplos


### Configuracion

Antes de Iniciar debes de iniciar asegurarse que cuenta con todo lo necesario para el laboratorio


#### Que se necesita

* Acceso a un navegador de Internet
* Tener instalado Visual Studio Code
* Tener instalado un Cliente de Api's
* Tener instalado Docker, Docker Compose, Git.
* Tener configurada una clave SSH
* Tener configurada Git
* Tener configurado Docker
* Tener configurada Docker Compose

---

### Descargar el repositorio de Github

1. Accede a por medio del navegador a la direccion: 
https://github.com/academia-consultec/api-design

2. Desplegar el boton `Code` y seleccionar `SSH` copiando con la url:

`git@github.com:academia-consultec/api-design.git`

3. Abre la terminal  

4. En la terminal ve al directorio del trabajo de tu usuario 

`cd /Users/{NombreUsuario}`

5. Crea un nuevo directorio y acceder al directorio

```
mkdir academia-consultec
cd academia-consultec
```

6. Clona el repositorio

git clone -b "module01" git@github.com:academia-consultec/api-design.git


### Aprovisione el entorno 

1. Accede a la carpeta 

`lab-01` 

2. Abre el archivo 

`docker-compose.yml`

3. levanta el entorno ejecutando en la terminal 

`docker compose up`

4. Valida que el servidor de Mocks este disponible accediendo por le navegador a:

`http://localhost:9000`

----

### Consumir apis de prueba

1. Abre el navegador

2. Abre el archivo `request.http`

4. Pruebe las peticiones pegandolas desde el navegador

* Consulta de usuario
* Consulta de imagenes del usuario
* Consulta de saldo del usuario
* Consulta de la factura del usuario
