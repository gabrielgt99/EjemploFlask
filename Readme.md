# Entorno de desarrollo
Para crear un etorno virtual de python se debe tener instalado en python el paquete ``virtualenv``, luego se inicializa con ``virtualenv venv`` y posteriormente se activa con ``source venv/bin/activate``, esto para un entorno Linux. Se debe hacer la instalacion con ``pip`` de los paquetes expuestos en ``REQUERIMENTS``.

# Inicializar Docker con MySQL
Para desplegar MySQL, verificar las credenciales y usuarios de acceso en el archivo ``mysql/docker-compose.yml``, luego se situa en la carpeta ``mysql`` y se ejecuta el comando ``docker-compose up -d``, recuerde que la bandera ``-d`` es para la ejecucion en segundo plano.

# Ejecucion de API en Flask
Es necesario estar situado en la raiz del proyecto ``/`` y ejecutar el comando ``python src/app.py``.

# Referencias
## MySQL
Se baso en https://github.com/tutorialesvip/Docker-Compose-MySQL

## Flask API
Se baso en https://www.youtube.com/watch?v=MvVqjQqSdM4

## Documentacion Swagger UI
Se baso en 