# Consulta de información universitaria con Django

Práctica académica de desarrollo web en Python para representar y consultar entidades de una universidad mediante modelos, vistas y plantillas Django.

## Funciones presentes
Las vistas de `Django/Universidad/views.py` consultan y muestran listados de:
- Carreras.
- Profesores.
- Estudiantes.
- Asignaturas.

El alcance comprobado es de consulta y presentación; no se describe como un CRUD completo.

## Organización
- `Django/manage.py`: administración del proyecto.
- `Django/Semana17/`: configuración y rutas.
- `Django/Universidad/`: modelos, vistas y plantillas.
- `Django/db.sqlite3`: archivo de base de datos incluido.

## Preparación local
Utiliza un entorno virtual de Python e instala una versión de Django compatible con el proyecto. No hay un archivo de dependencias fijadas, por lo que la compatibilidad debe comprobarse antes de ejecutar.

Desde `Django/`, con la configuración de base de datos revisada:
```bash
python manage.py check
python manage.py migrate
python manage.py runserver
```
Consulta las rutas definidas en `Semana17/urls.py` y `Universidad/urls.py`.

## Aprendizajes
Relaciones entre entidades, consultas con el ORM y renderizado de información en plantillas. Es una práctica universitaria y no un sistema institucional en producción.
