 # CookList - Gestor Inteligente de Recetas y Suministros

CookList es una aplicación web desarrollada en **Python** utilizando el framework **Flask**. El objetivo del proyecto es permitir a los usuarios gestionar sus propias recetas y automatizar la generación de listas de compras basadas en los ingredientes necesarios, optimizando la planificación alimenticia.

## 🚀 Características Principales

* **Gestión de Usuarios:** Sistema de registro e inicio de sesión seguro con manejo de sesiones (cookies).
* **Biblioteca de Recetas:** Creación, edición y visualización de recetas personalizadas de forma intuitiva.
* **Generador de Suministros:** Algoritmo dinámico que consolida los ingredientes de las recetas seleccionadas para generar una lista de compras organizada.

## 🛠️ Stack Tecnológico

* **Backend:** Python 3.x, Flask.
* **Base de Datos:** mySQL (SQL para la persistencia de usuarios, recetas e ingredientes).
* **Frontend:** HTML5, CSS3, Jinja2 (Motor de plantillas).
* **Control de Versiones:** Git & GitHub.

## 📁 Estructura del Proyecto

* `app.py`: Punto de entrada de la aplicación, configuración del servidor y manejo de rutas.
* `api.py`: Capa de lógica intermedia que gestiona la comunicación entre las rutas y la base de datos, centralizando las operaciones CRUD.
* `database.db`: Base de datos relacional para la persistencia de la información.
* `templates/`: Vistas de la aplicación (Login, Registro, Dashboard, Recetas).
* `static/`: Recursos estáticos (Estilos CSS, recursos visuales).

## ⚙️ Instalación y Ejecución

1. **Clonar el repositorio:**
   ```bash
   git clone [https://github.com/TU_USUARIO/CookList-Flask-App.git](https://github.com/TU_USUARIO/CookList-Flask-App.git)
2. **Preparar el entorno e instalar dependencias:** Ejecuta el script de configuración
   ```bash
   bash 1.sh
3. **Preparar base de datos y dependencias:**
   ```bash
   bash 2.sh
4. **Ejecutar la api:**
   ```bash
   python3 api.py
5. **Ejecutar la apliación:** Desde otra terminal
   ```bash
   pipenv shell
   python3 app.py
6. **Acceder a la pagina web desde el navegador:**
    La aplicación estará disponible en: http://127.0.0.1:5000

## 👥 Créditos y Colaboradores

Este proyecto fue desarrollado como parte de la currícula de la Universidad de Buenos Aires (FIUBA).

* Agustin Bermudez - [GitHub Profile](https://github.com/AgBermudez)
* Alejandro Mendez - [GitHub Profile](https://github.com/AlejandroMendez7)
* Tiago André Calderón - [GitHub Profile](https://github.com/tiagoquemero)
* Mateo Gonzalez Pautaso - [GitHub Profile](https://github.com/MateoGonzalezPautaso)
* Cristian Ezequiel Urbina - [GitHub Profile](https://github.com/ezeurbina)
* Ignacio Verruno - [GitHub Profile](https://github.com/NachoVerruno)

## Nota

Este repositorio es un fork del proyecto original, mantenido para fines de portfolio personal y documentación técnica. 