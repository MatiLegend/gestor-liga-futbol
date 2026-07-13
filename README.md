# ⚽ Gestor de Liga de Fútbol (ANFA)

![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

Este es un sistema web desarrollado en **Django (Python)** para la gestión de torneos y equipos de fútbol. Permite llevar el control de la tabla de posiciones, calendario de partidos, noticias y detalles de cada equipo divididos por zonas (Norte, Centro, Sur) y categorías (ej. Tercera A).

## 🚀 Características Principales

- **Gestión de Equipos**: Registro de información de clubes, incluyendo goles a favor, en contra y diferencia de goles.
- **Tabla de Posiciones**: Visualización clara de la clasificación.
- **Calendario de Partidos**: Programación de fechas y registro de resultados.
- **Noticias y Galería**: Sección de novedades y actualizaciones visuales de la liga.
- **Segmentación Geográfica**: Clasificación de equipos por zonas (Norte, Centro, Sur).

## 🛠️ Tecnologías Utilizadas

- **Backend**: Python, Django
- **Frontend**: HTML5, CSS3 (Diseño responsivo)
- **Base de Datos**: SQLite
- **Manejo de Archivos/Imágenes**: Pillow

## 💻 Instalación Local

Para ejecutar este proyecto en tu entorno local, sigue estos pasos:

1. **Clona este repositorio**:
   ```bash
   git clone https://github.com/MatiLegend/gestor-liga-futbol.git
   cd gestor-liga-futbol
   ```

2. **Crea y activa un entorno virtual (recomendado)**:
   ```bash
   python -m venv venv
   # En Windows:
   venv\Scripts\activate
   # En macOS/Linux:
   source venv/bin/activate
   ```

3. **Instala las dependencias principales**:
   ```bash
   pip install django pillow
   ```

4. **Aplica las migraciones de la base de datos**:
   ```bash
   python manage.py migrate
   ```

5. **Inicia el servidor de desarrollo**:
   ```bash
   python manage.py runserver
   ```

6. Visita `http://127.0.0.1:8000/` en tu navegador.

## 👤 Autor

**Matias** - [MatiLegend](https://github.com/MatiLegend)
