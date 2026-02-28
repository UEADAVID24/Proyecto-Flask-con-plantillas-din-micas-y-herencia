# Sistema Avanzado de Gestión de Inventario – Flask

##Descripción del Proyecto
Este proyecto corresponde a un **Sistema Avanzado de Gestión de Inventario** desarrollado con **Flask**, como continuación del proyecto iniciado en las semanas 9 y 10.  
El sistema permite administrar productos de una tienda (ferretería) aplicando **Programación Orientada a Objetos (POO)**, uso de **colecciones** y **operaciones CRUD reales** conectadas a una base de datos **SQLite**.

---

##Objetivos
- Aplicar Programación Orientada a Objetos para estructurar el sistema.
- Utilizar colecciones de Python para la gestión de datos.
- Implementar operaciones CRUD reales (Crear, Leer, Actualizar, Eliminar).
- Almacenar la información de manera persistente en SQLite.
- Integrar formularios web para la gestión del inventario.

---

##Tecnologías Utilizadas
- Python 3
- Flask
- SQLite
- HTML + Jinja2
- Visual Studio Code

---

##Estructura del Proyecto
Mi_proyecto_flask_Clinton_Alvarado/
│
├── app.py
├── db.py
├── init_db.py
├── models/
│ ├── producto.py
│ └── inventario.py
├── database/
│ └── database.db
├── templates/
│ ├── base.html
│ ├── index.html
│ ├── productos.html
│ ├── agregar_producto.html
│ ├── editar_producto.html
│ └── clientes.html
├── static/
├── requirements.txt
└── README.md

---

##Programación Orientada a Objetos (POO)
- **Clase Producto:** representa un producto con atributos como ID, nombre, cantidad y precio.
- **Clase Inventario:** gestiona los productos y contiene los métodos CRUD conectados a SQLite.

---

##Uso de Colecciones
- Se utilizan **listas** para manejar los conjuntos de productos obtenidos desde la base de datos.
- Inicialmente se emplearon **diccionarios** para la gestión del inventario en memoria.
- Las colecciones permiten una gestión eficiente de los datos del inventario.

---

##Base de Datos SQLite
- Se utiliza SQLite para el almacenamiento persistente de los datos.
- La base de datos contiene la tabla `productos`.
- La conexión se centraliza en el archivo `db.py`.

---

##Operaciones CRUD Implementadas
- **Crear:** agregar productos mediante formulario web.
- **Leer:** mostrar productos almacenados en la base de datos.
- **Actualizar:** modificar cantidad y precio de un producto.
- **Eliminar:** eliminar productos del inventario.

---

##Interfaz de Usuario
- El sistema cuenta con formularios web para gestionar el inventario.
- Se implementa un submenú que permite realizar todas las operaciones CRUD.

---

##Ejecución del Proyecto
1. Activar el entorno virtual:
   .\venv\Scripts\activate
2. Crear la base de datos:
   py init_db.py
3. Ejecutar la aplicación:
   py app.py
4. Abrir en el navegador:
   http://127.0.0.1:5000/productos

---

##Autor
**Clinton David Alvarado Chongo**

Proyecto académico – Desarrollo de aplicaciones web con Flask
