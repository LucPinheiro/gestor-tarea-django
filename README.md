## Gestor de Tareas - Aplicación Web y Movil con Django

Aplicación web desarrollada con Django para la gestión completa de tareas mediante operaciones CRUD, importación/exportación CSV y una interfaz moderna inspirada en herramientas tipo Trello y Odoo.

---

## Funcionalidades principales

- Crear tareas mediante formularios web.
- Visualizar tareas en:
  - Vista Kanban
  - Vista Lista
- Editar tareas existentes.
- Eliminar tareas individualmente o en lote.
- Confirmación antes de eliminar registros.
- Importación masiva de tareas mediante archivos CSV.
- Exportación de tareas a CSV.
- Sistema de autenticación:
  - Login
  - Logout
  - Protección de vistas privadas
- Diseño responsive para escritorio y móvil.
- Interfaz moderna con Bootstrap 5 y CSS personalizado.

---

## Tecnologías utilizadas

- Python 3
- Django 5
- SQLite
- Bootstrap 5
- HTML5
- CSS3
- JavaScript
- ORM de Django
- ModelForm
- CSV module de Python

---

## Características técnicas implementadas

- Arquitectura MVC/MVT de Django.
- Uso de `models.py`, `views.py`, `forms.py` y `urls.py`.
- Sistema de rutas personalizado.
- Templates reutilizables mediante `base.html`.
- Uso de mensajes dinámicos (`messages framework`).
- CRUD completo.
- Sistema de filtros y búsqueda.
- Importación y exportación de datos CSV.
- Diseño responsive y experiencia de usuario moderna.

---

## Objetivo del proyecto

El objetivo de esta aplicación es facilitar la organización y gestión de tareas personales o profesionales mediante una interfaz intuitiva y funcionalidades avanzadas de administración de datos.

## Estructura del proyecto

## Estructura del proyecto

```bash
gestor_tareas/
│
├── manage.py
├── db.sqlite3
├── requirements.txt
├── README.md
│
├── mi_proyecto/
│   ├── __init__.py
│   ├── asgi.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
│
├── tareas/
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── forms.py
│   ├── models.py
│   ├── tests.py
│   ├── views.py
│   ├── urls.py
│   │
│   ├── migrations/
│   │   ├── __init__.py
│   │   └── ...
│   │
│   ├── static/
│   │   └── tareas/
│   │       └── style.css
│   │
│   └── templates/
│       └── tareas/
│           ├── base.html
│           ├── lista.html
│           ├── detalle.html
│           ├── formulario.html
│           ├── confirmar_eliminar.html
│           ├── importar_csv.html
│           └── login.html
│
├── media/
│
└── venv/
```
