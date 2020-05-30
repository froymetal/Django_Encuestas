# Django_Encuestas
Un sistema básico para realizar encuestas en Django

Para activar el proyecto

1. Descargar el proyecto

2. Crear la base de datos con los comandos desde consola
  python manage.py makemigrations
  python manage.py migrate

3. Crear un super usuario para administrar la informacion
  python manage.py createsuperuser

4. Arrancar el servidor
  pyrhon manage.py runserver

5. Ingresar a la pagina de admin para crear las encuestas con las credenciales de super usuario
  127.0.0.1:8000/admin

6. Ingresar al sistema y llenar las encuestas
  127.0.0.1:8000/
