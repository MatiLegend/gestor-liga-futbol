# 🏆 Gestor Liga de Fútbol (ANFA)

¡Bienvenido al repositorio oficial del **Gestor Liga de Fútbol**! Este proyecto es una aplicación web desarrollada con **Django y Python**, diseñada para gestionar noticias, multimedia y contenido relacionado con ligas de fútbol amateur.

## 🚀 Tecnologías Utilizadas

- **Backend:** Python, Django
- **Frontend:** HTML5, CSS3, JavaScript, Bootstrap 5
- **Base de Datos:** SQLite (Configuración por defecto)
- **Control de Versiones:** Git & GitHub

## ✨ Características Principales

- **Gestión de Multimedia:** Galería de imágenes y lista de reproducción de videos interactiva.
- **Sección de Noticias:** Carrusel dinámico para mantener a los usuarios informados.
- **Diseño Responsivo:** Interfaz amigable y adaptable a dispositivos móviles usando Bootstrap.
- **Panel de Administración:** Acceso seguro mediante el panel por defecto de Django para gestionar el contenido.

## 🛠️ Instalación y Ejecución Local

Para ejecutar este proyecto en tu propia máquina, sigue estos pasos:

1. **Clona este repositorio:**
   ```bash
   git clone https://github.com/MatiLegend/gestor-liga-futbol.git
   cd gestor-liga-futbol
   ```

2. **Crea y activa un entorno virtual (Recomendado):**
   ```bash
   python -m venv venv
   # En Windows
   venv\Scripts\activate
   # En macOS/Linux
   source venv/bin/activate
   ```

3. **Instala las dependencias necesarias:**
   Asegúrate de instalar Django y Pillow para el manejo de imágenes.
   ```bash
   pip install django Pillow
   ```

4. **Realiza las migraciones de la base de datos:**
   ```bash
   python manage.py makemigrations
   python manage.py migrate
   ```

5. **Inicia el servidor de desarrollo:**
   ```bash
   python manage.py runserver
   ```
   *Abre tu navegador y entra a `http://127.0.0.1:8000/`*

## 🧑‍💻 Autor

- **MatiLegend** - *Desarrollador y Creador* - [GitHub](https://github.com/MatiLegend)

---
*Este proyecto fue diseñado con el objetivo de demostrar habilidades de desarrollo web fullstack con Django para futuras oportunidades profesionales.*
