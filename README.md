# Proyecto-Final-CoderHouse

# MyDailyDrive
Ejemplo de Blog hecho con Django!

Este es un proyecto de ejemplo de un blog desarrollado utilizando el framework Django. El blog cuenta con funcionalidades como registro de usuarios, inicio de sesión, cierre de sesión, cambio de imagen de perfil, cambio de contrasenas, creación de publicaciones, edición de publicaciones, comentarios y eliminación de publicaciones.



# Requisitos
- Python
- Django
- django-crispy-forms
- Pillow


  
# Instalación
Asegúrate de tener Python y Django instalados en tu sistema. 
1. Clona el repositorio:
  gh repo clone tomasmantegazza/Proyecto-Final-CoderHouse

2. Navega al directorio del proyecto:
  cd django_project

3. Instala las dependencias:
   pip install -r requirements.txt

4. Aplica las migraciones de la base de datos:
   python manage.py migrate

5. Crea un superusuario para acceder al panel de administración:
   python manage.py createsuperuser

6. Inicia el servidor de desarrollo:
   python manage.py runserver

7. Probar el usuario maestro, donde hay posts y perfiles hechos.
usuario administrador
usuario: TomasMantegazza
contraseña: holacomova

La aplicación estará disponible en http://127.0.0.1:8000/



# Testeo
-Regístrate como un nuevo usuario en la página de inicio, en el boton de arriba a la derecha "Register"
-Inicia sesión con tu nueva cuenta, en el boton de arriba a la derecha "Login" o desde el redirect luego de registrarte
-Cambia tu imagen e informacion de tu perfil desde la página de perfil de usuario, en el boton Profile arriba a la derecha
-Crea nuevos posts desde la página de inicio, en el boton "New Post"
-Modifica tus posteos existentes desde la página de detalle de la publicación, entrando al post y tocando "update"
-Comenta en las publicaciones de otros usuarios desde la página de detalle de la publicación.
-Elimina tus propias publicaciones desde la página de detalle de la publicación o desde la página de inicio.
-Cierra sesión cuando hayas terminado.


# Funcionalidades
  - Home: Navbar con botones para cada categoria
  - MyDailyDrive y Home: llevan al inicio de la pagina
  - About: lleva a informacion adicional de la pagina
  - Events: un apartado para ver calendario de eventos y fotos
  - Contact: un apartado para contactarte con nosotros!
  - Login: iniciar sesion
  - Register: registrar usuario
  - New post(solo si hay una sesion iniciada): crear post
  - Comment(solo si hay una sesion iniciada): comentar un post

# Video demostrativo del proyecto
https://www.loom.com/share/627d087258d64dc7b817c4229214b3a1?sid=f3263606-79e6-4ad4-bc45-4ae6df1830b6

# Plantilla con casos de prueba
https://docs.google.com/spreadsheets/d/19216rgaTlZOlsoy52jrgcDQC1yeuqX9JFov6B0Iusy8/edit?usp=sharing


# Estructura del Proyecto
El proyecto está organizado de la siguiente manera:

blog: Aplicación principal del blog.
user: Aplicación de usuarios y autenticación.
static: Carpeta que contiene archivos estáticos como CSS e imágenes.
templates: Carpeta que contiene las plantillas HTML de la aplicación.
media: Carpeta donde se almacenan los archivos multimedia como las imágenes de perfil de los usuarios.
manage.py: Script de gestión de Django para realizar tareas administrativas.

# Tecnologías Utilizadas
Python
Django
HTML/CSS
Bootstrap (opcional)
