# Django Tutorial

Este proyecto es un tutorial basado en la [documentación oficial de Django - Writing your first Django app, part 1](https://docs.djangoproject.com/en/6.0/intro/tutorial01/).

## Descripción

Este tutorial te guiará a través de los conceptos fundamentales de Django, incluyendo:

- Instalación y configuración de Django
- Creación de un proyecto Django
- Creación de aplicaciones Django
- Modelos y bases de datos
- La interfaz de administración
- Vistas y URLs

## Requisitos

- Python 3.8+
- pip (gestor de paquetes de Python)

## Instalación

1. Clona el repositorio:

```bash
git clone <URL_DEL_REPOSITORIO>
cd djangotutorial
```

1. Crea un entorno virtual:

```bash
python -m venv venv
```

1. Activa el entorno virtual:
   - En Windows:

   ```bash
   venv\Scripts\activate
   ```

   - En macOS/Linux:

   ```bash
   source venv/bin/activate
   ```

2. Instala las dependencias:

```bash
pip install django
```

## Estructura del Proyecto

```
djangotutorial/
├── manage.py
├── djangotutorial/
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
└── README.md
```

## Uso

Para ejecutar el servidor de desarrollo:

```bash
python manage.py runserver
```

El servidor estará disponible en `http://localhost:8000/`

## Referencias

- [Django Documentation](https://docs.djangoproject.com/)
- [Writing your first Django app, part 1](https://docs.djangoproject.com/en/6.0/intro/tutorial01/)

## Licencia

Este proyecto es educativo y sigue la licencia de Django.

## Versiones

### rc95 28/05/2026 00:17 - 0.0.4

- Se crea el archivo `.gitignore`
- Se cambian las configuraciones en el archivo `mysite/settings.py`
- Se crean las tablas en la base de datos con el comando `python manage.py migrate`

### rc95 28/05/2026 00:12 - 0.0.3

- Se crea la vista `index` de `polls`, accesible desde `http://localhost:8000/polls/`

### rc95 28/05/2026 00:06 - 0.0.2

- Se crea el proyecto `polls` con el comando `python manage.py startapp polls`
- Se crea el archivo `README.md`

### rc95 27/05/2026 23:57 - 0.0.1

- Se crea el proyecto con el comando `python -m django startproject mysite djangotutorial`
