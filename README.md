###### Test de correo con PHP Mailer

Mini proyecto en composer para testear si funciona correctamente un envío de correo usando los parámetros SMTP.

Crear archivo .env a partir de archivo .env.example y definir los parámetros.

HOST=smtp-relay.gmail.com\
USERNAME=\
PASSWORD=\
PORT=587 Para TLS y 465 SSL, si usas SSL modifica index.php\
FROM_MAIL=me@example.com\
FROM_NAME=Example\
TO_MAIL=you@example.com\
TO_NAME="Joe Doe"\

Ejecuta el comando de envío usando

`php index.php`