# **Github Actions - Demo**

## Herramientas y tecnologías usadas

- Docker Windows / Ubuntu 18.04

- Python 3.10

## Pasos a seguir

### Creando carpeta de proyecto

- Crear carpeta .github/workflows

- Crear archivo **nombre del archivo**.yml

- Configurar la acción de la siguiente forma:

    * Nombre de la acción.

    * Evento de ejecución.

    * Definir sistema operativo.

    * Definir los pasos a realizar.

### Generar token de DockerHub

- Ingresar a DockerHub

- Crear un repositorio

### Subir una imagen a DockerHub

- cd path/Dockerfile folder

- docker build -t username/repository:**tagname** .

- docker push username/repository:**tagname**

### Configurando repositorio de Github

- Ir al repositorio

- Ir a la pestaña de configuraciones / Settings

- Ir al menú Secrets / Actions