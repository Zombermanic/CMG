instale las bibliotecas necesarias para ejecutar el proyecto:
```
pip install -r requisitos.txt
```
Para poder tener el primer acceso y configurar la aplicación, ejecutemos el comando
'migrate' para generar la base de datos Django predeterminada (SQLite). Y luego crea el superusuario:
```
python manage.py migrate
python manage.py createsuperuser
Apodo/Usuario: admini
Correo electrónico: admin@mail.com
Contraseña: 
Contraseña de nuevo:
```

Para iniciar el servidor después de este paso debes:
```
python manage.py runserver
```


Para ver si todo funciona como se esperaba, vaya a la siguiente dirección:
[http://localhost:8000/](http://localhost:8000/)

O puedes tener acceso al administrador de Django:
[http://localhost:8000/admin](http://localhost:8000/admin)