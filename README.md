Pasos que se necesitan para ejecutar el backend

1 Una vez que clonan el repositorio, crear una base de datos en mysql

2 en la raíz del proyecto de backend ejecutar los siguientes comandos.

3 copy .env.example .env

4 composer install

5 php artisan key:generate

6 modificar el .env con las variables de entorno de su base de datos.

7 php artisan migrate --seed

8 php artisan serve 

no es necesario poner --host=0.0.0.0 junto al serve ya que la aplicacion funciona con la direccion de localhost
