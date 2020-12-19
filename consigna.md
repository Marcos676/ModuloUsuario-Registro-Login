# ModuloUsuarioCompleto
Ejercitación registro y login de usuarios

Debe crear una aplicacion modularizada con tres archivos: app.js, usuarios.js y usuarios.json.
Puede recibir los siguientes comandos por consola:

- registro 'nombre' 'mail' 'contraseña'
Nos debe crear un nuevo usuario con los datos que recibe.

- login 'mail' contraseña'
Si existe un usuario con el mail y la contraseña que recibe, mostrarle al usuario un mensaje
de bienvenida. Sino, notificar que no se pudo iniciar sesión.


- eliminar 'mail' contraseña'
Si existe un usuario con el mail y la contraseña que recibe, eliminar dicho usuario y mostrar
por consola que se pudo eliminar el usuario. Sino, notificar que no se pudo eliminar.


Extras
Al registrar:

- Verificar si el mail que introduce el usuario tiene el caracter ‘@’.

- Si ya existe un usuario registrado con ese mail, informar sobre el problema y no crear el
usuario.

- Verificar que la contraseña tenga al menos una letra y un número.
