# Requerimientos
 - Python version 3
 - Docker
 - Paquetes de Python
    - flask
    - Flask-SQLAlchemy
    - flask-marshmallow
    - marshmallow-sqlalchemy
    - pymysql

# Entorno de desarrollo
Para crear un etorno virtual de python se debe tener instalado en python el paquete ```virtualenv```.
Luego se inicializa con 

```bash
virtualenv venv
```
Se activa con el entorno virtual con

```bash
source venv/bin/activate
```

esto para un entorno Linux. Se debe hacer la instalacion con ``pip`` de los paquetes expuestos en ``REQUERIMENTS``.

# Inicializar Docker con MySQL
Para desplegar MySQL, verificar las credenciales y usuarios de acceso en el archivo ``mysql/docker-compose.yml``, situandose en la carpeta ``mysql`` se levanta el contenedo con el comando 

```bash
docker-compose up -d
```

recuerde que la bandera ``-d`` es para la ejecucion en segundo plano.

# Ejecucion de API en Flask
Posicionado en la raiz del proyecto ```/``` se levanta el API con 

```bash
python src/app.py
```

# Referencias
## MySQL
Se baso en https://github.com/tutorialesvip/Docker-Compose-MySQL

## Flask API
Se baso en https://www.youtube.com/watch?v=MvVqjQqSdM4

## Documentacion Swagger UI
Se baso en 

## License
[MIT](https://choosealicense.com/licenses/mit/)
