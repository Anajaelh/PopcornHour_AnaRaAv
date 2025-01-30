# PopcornHour

PopcornHour es una plataforma web para recomendar, calificar y discutir sobre películas y series. Está diseñada con Flask y SQLAlchemy para ofrecer una experiencia dinámica e interactiva.

## 🚀 Características
- Registro e inicio de sesión de usuarios.
- Diferentes roles de usuario: estándar y moderador.
- Moderadores pueden subir películas y series.
- Usuarios estándar pueden calificar, comentar y participar en discusiones.

## 📂 Estructura del proyecto

## 🛠️ Instalación y configuración

1. Clona el repositorio:
   ```bash
   git clone <repo_url>
   cd PopcornHour
2. Crea un entorno virtual y actívalo:
   ```bash
   python -m venv venv
   source venv/bin/activate  # En Windows: venv\Scripts\activate
3. Instala las dependencias:
 ```bash
pip install -r requirements.txt
 ```
4. Inicia la aplicación
## 🗃️ Base de datos
El proyecto utiliza Supabase como base de datos predeterminada. Los modelos incluyen:

User: Almacena información de usuarios.
Movie: Información sobre películas y series.
Rating: Calificaciones de los usuarios.
Comment: Comentarios sobre películas.
## 🛡️ Autenticación y autorización
Se utiliza Flask-Login para manejar:

Registro de usuarios.
Inicio de sesión.
Rutas protegidas según el tipo de usuario.

## 📋 Próximos pasos
Diseño de interfaces más detalladas.
Implementación de la funcionalidad de subida de películas.
Creación de una página de detalles de película.
