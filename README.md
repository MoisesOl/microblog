Microblog

Microblog es un proyecto de plataforma de microblogging desarrollado en Python con el framework web Flask. Está diseñado para simular funcionalidades básicas de redes sociales como Twitter, permitiendo a los usuarios registrarse, publicar mensajes cortos (tweets), seguir a otros usuarios y interactuar mediante respuestas y likes.
Características Principales

    Autenticación de Usuarios: Permite a los usuarios registrarse, iniciar sesión y gestionar sus perfiles.

    Publicación de Tweets: Los usuarios pueden escribir y publicar mensajes cortos que aparecen en su timeline y en los timelines de sus seguidores.

    Seguimiento de Usuarios: Funcionalidad para seguir a otros usuarios y ver tweets exclusivamente de aquellos a quienes se sigue.
    
    Interfaz de Usuario Intuitiva: Implementación de una interfaz amigable utilizando HTML, CSS y Jinja2 para la generación de plantillas dinámicas.

    Persistencia de Datos: Utilización de SQLAlchemy como ORM para la gestión de la base de datos SQLite, donde se almacenan usuarios, tweets y relaciones de seguimiento.

Estructura del Repositorio

    app.py: Punto de entrada de la aplicación Flask y configuración principal.

    models.py: Define los modelos de datos utilizando SQLAlchemy, incluyendo la estructura de usuarios y tweets.

    routes.py: Contiene las rutas y controladores (handlers) que manejan las peticiones HTTP para la autenticación de usuarios, publicación de tweets y gestión de relaciones de seguimiento.

    templates/: Carpeta que contiene las plantillas HTML utilizadas para la generación de las páginas web.

    static/: Directorio para archivos estáticos como imágenes, hojas de estilo CSS y scripts JavaScript.

    requirements.txt: Archivo que lista todas las dependencias de Python necesarias para ejecutar la aplicación.

    migrations/: Directorio generado por Flask-Migrate para gestionar las migraciones de la base de datos.

Tecnologías Utilizadas

    Backend: Python, Flask
    Base de Datos: SQLite (con SQLAlchemy)
    Frontend: HTML, CSS (Bootstrap), Jinja2
    Motor de búsqueda: ElasticSearch
