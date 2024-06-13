<h1>Microblog</h1>

<h2>Microblog es un proyecto de plataforma de microblogging desarrollado en Python con el framework web Flask. Está diseñado para simular funcionalidades básicas de redes sociales como Twitter, permitiendo a los usuarios registrarse, publicar mensajes cortos (tweets), seguir a otros usuarios y interactuar mediante respuestas y likes.</h2>
    
<h3>Características Principales</h3>

<ul>
<li>Autenticación de Usuarios: Permite a los usuarios registrarse, iniciar sesión y gestionar sus perfiles.</li>

<li>Publicación de Tweets: Los usuarios pueden escribir y publicar mensajes cortos que aparecen en su timeline y en los timelines de sus seguidores.</li>

<li>Seguimiento de Usuarios: Funcionalidad para seguir a otros usuarios y ver tweets exclusivamente de aquellos a quienes se sigue.</li>

<li>Tareas en Segundo Plano: Funcionalidad para realizar múltiples tareas en segundo plano como envíos de correo y la descarga de tus Tweets.</li>
    
<li>Interfaz de Usuario Intuitiva: Implementación de una interfaz amigable utilizando HTML, CSS, AJAX y Jinja2 para la generación de plantillas dinámicas.</li>

<li>Persistencia de Datos: Utilización de SQLAlchemy como ORM para la gestión de la base de datos SQLite, donde se almacenan usuarios, tweets y relaciones de seguimiento.</li>

<li>Multilenguaje: Utilización de Flask-Babel para tener una página facilmente escalable entre multiples idiomas. Actualmente posee Inglés y Español y es escogido según la preferencia de tu navegador.</li>

<li>Traducciones en Tiempo Real: Posibilidad de traducir en tiempo real tweets de otros idiomas al lenguaje del usuario.</li>

<li>Reloj Mundial Dinámico: Conversión del Tiempo Universal Cordinado (UTC) a la zona horaria del usuario para la internacionalización de la pagina web.</li>
</ul>

<h3>Estructura del Repositorio</h3>

<ul>
<li>app.py: Punto de entrada de la aplicación Flask y configuración principal.</li>

<li>models.py: Define los modelos de datos utilizando SQLAlchemy, incluyendo la estructura de usuarios y tweets.</li>

<li>routes.py: Contiene las rutas y controladores (handlers) que manejan las peticiones HTTP para la autenticación de usuarios, publicación de tweets y gestión de relaciones de seguimiento.</li>

<li>templates/: Carpeta que contiene las plantillas HTML utilizadas para la generación de las páginas web.</li>

<li>static/: Directorio para archivos estáticos como imágenes, hojas de estilo CSS y scripts JavaScript.</li>

<li>requirements.txt: Archivo que lista todas las dependencias de Python necesarias para ejecutar la aplicación.</li>

<li>migrations/: Directorio generado por Flask-Migrate para gestionar las migraciones de la base de datos.</li>
</ul>

<h3>Tecnologías Utilizadas</h3>

<ul>
<li>Backend: Python, Flask</li>
<li>Base de Datos: SQLite (con SQLAlchemy)</li>
<li>Frontend: HTML, CSS (Bootstrap), Jinja2</li>
<li>Motor de búsqueda: ElasticSearch</li>
</ul>
