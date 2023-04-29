# Centribal

Centribal es una app para manejos de articulos y pedidos.

# Owner

- Karina Vargas Gonzalez

# New Features!

- App para el manejo de los articulos y pedidos

### Requeriments

- Python 3.8

### Installation

Instalaciones de dependencias y devDependencias para empezar.
Para la instalación, tu debes clonar el siguiente repositorio:

- [Repositorio](https://github.com/kary1806/centribal_backend.git)

#### Para el ambiente de desarrollo

- **Contenedor docker:**

```sh
$ git clone <repositorio>
$ docker-compose build
$ docker-compose up
```

_Nota: verificar que se ejecuten todas las migraciones (probablemente se deba correr docker-compose up nuevamente)._

```sh
# Para correr el shell de django
$ docker-compose run centribal_backend python manage.py shell
```

```sh
# Para crear un super user en el django
$ docker-compose run centribal_backend python manage.py createsuperuser
```

Para entrar en la consola del contenedor, en otra terminal, ejecutar:

```sh
# Tiene que estar corriendo el contenedor para poder ejecutar
$ docker-compose exec centribal_backend bash
```

```sh
# Para ejecutar los test unitarios
$ docker-compose run centribal_backend python manage.py test
```

Para interactuar con los endpoints se necesita un Api Key puede ser generada desde el backoffice:

```sh
$ url_backoffice = http://0.0.0.0:8000/
```

# Url Documentacion Endpoints

```sh
$ url_docs_swagger = http://0.0.0.0:8000/docs/
```
