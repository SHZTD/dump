# dump
Inicializar todo:
Cambiar las rutas de la API endpoint.
Front (js & html) y Back (SpringBoot w/ JPA + try de implementar el Swagger/OpenAPI)

TODO:

[X] Login (la BD almacena usuario y contraseña en AES-CBC) - (Se tiene que modificar la SECRET-KEY & IV) - (O remplazarlo mas tarde por BCrypt)
    (Para futuro - mejorar las llamadas del cliente al enviar los datos a la api con request params no es la mejor del mundo)

[X] Inserts con ENUMS

[~] Registrar usuarios con sus respectivas contraseñas (Hacer los controllers) 

[~] Mas opciones de CRUD - (Eliminar alumnos, Update...)

[~] Reparar los random null exceptions del backend (no hay problemas con 500 o error codes)

[~] Eventualmente se deben de dejar de hacer las pruebas en una base de datos sencilla, hace falta traspasarse al ER que tenemos,
hacer mas front, y un par mas de controllers
