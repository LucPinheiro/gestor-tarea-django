## Gestor de Tarea

# Estructura del proyecto

```text
gestor_tareas/
│
├── manage.py
├── db.sqlite3
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
│   │
│   ├── migrations/
│   │   └── __init__.py
│   │
│   └── templates/
│       └── tareas/
│           ├── lista.html
│           ├── formulario.html
│           ├── confirmar_eliminar.html
│           └── importar_csv.html
│
└── venv/
