# Gestor Academico

## Descripción
El proyecto se trata sobre una API qe hace la funcion de un gestor academico de alumnos y maestros, esto con algunas librerias y tecnologias las cuales son:

Node.js
MongoDB
Express
librerías adicionales:
Bcrypt
Mongoose
JWT

El sistema esta hecho con dos roles: TEACHER_ROLE y STUDENT_ROLE, donde el registro y las funciones serán diferentes para cada uno.

## Funciones del Alumno
El Alumno podrá realizar las siguientes acciones:

Registrarse como STUDENT_ROLE por defecto y loguearse.
No podrá asignarse a un curso que ya tenga alumnos asignados.
Visualizar los cursos a los que está asignado.
Editar y eliminar su perfil.

## Funciones del Maestro
El Maestro podrá realizar las siguientes acciones:

Registrarse como TEACHER_ROLE y loguearse.
Crear, eliminar y visualizar los cursos que posea.
Si un maestro elimina un curso con alumnos asignados, los alumnos serán desasignados automáticamente del curso.
Aspectos a Tener en Cuenta
Tecnologías Utilizadas
Node.js: Entorno de ejecución para el desarrollo del servidor.
MongoDB: Base de datos NoSQL para almacenar la información.
Express: Framework de Node.js para facilitar el desarrollo del backend.
Bcrypt: Librería para el hash de contraseñas.
Mongoose: Librería para interactuar con MongoDB en Node.js.
JWT (JSON Web Token): Para la gestión de autenticación y autorización.
