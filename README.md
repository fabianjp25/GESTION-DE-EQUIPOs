# 📦 Sistema de Gestión de Equipos

Este proyecto es un sistema de gestión de equipos desarrollado con **FastAPI**, **SQLite**, y **HTML con Bootstrap** para el frontend. Permite registrar, listar y administrar información de equipos, con una interfaz sencilla y un backend escalable.

---

## 🚀 Tecnologías usadas

- [FastAPI](https://fastapi.tiangolo.com/)
- [SQLite](https://www.sqlite.org/)
- [SQLAlchemy](https://www.sqlalchemy.org/)
- [Jinja2](https://jinja.palletsprojects.com/)
- [Bootstrap 5](https://getbootstrap.com/)

---

## 🛠️ Estructura del proyecto

project/
│
├── app/
│ ├── crud/ # Funciones de acceso a datos (CRUD)
│ │ └── equipo.py
│ ├── models/ # Modelos SQLAlchemy
│ │ └── equipo.py
│ ├── routers/ # Rutas de la API (FastAPI)
│ │ └── equipo.py
│ ├── schemas/ # Esquemas Pydantic para validación
│ │ └── equipo.py
│ ├── templates/ # Archivos HTML
│ │ └── login.html
│ └── database.py # Configuración de la conexión a la base de datos
│
├── main.py # Punto de entrada del backend
├── seed.py # Archivo opcional para poblar la base de datos
├── test.db # Base de datos SQLite de ejemplo
├── index.html # Página principal (bienvenida)
├── login.html # Login básico (HTML)
├── requirements.txt # Dependencias del proyecto
└── README.md # Este archivo

--------------------------------------------------------------------------

🔧 Instalación y Configuración
1- Crear entorno virtual
python -m venv venv
venv\Scripts\activate


2- Instalar dependencias
pip install fastapi uvicorn sqlalchemy pydantic

3- Estructurar el proyecto como el árbol mostrado arriba.

Para visualizar la aplicacion, debe abrir el index.html

-------------------------------------------

Este proyecto está desarrollado por Alejandro Payares, Darwin Mercado y Fabian Julio para fines académicos y puede adaptarse libremente.
