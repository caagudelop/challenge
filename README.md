# WChallenge
El proyecto esta distribuido en un proyecto principal que contiene los dos submodulos que son dos web service independientes.

# PermissionAlbumService
En este proyecto se encuentra la segunda parte del WChallenge que se encarga de gestionar el sistema de permisos para los album

Para los permisos se implemento una cadena que los va a guardar, los identifiqué con dos letras L(lectura) y E(escritura), y en el campo se guardarian asi "L,E", y el servicio que los modifica recibe albumId, userId y la cadena permisos. Si se ingresa un albumId y userId que ya existen el registro se modifica, si no se ingresa como uno nuevo.

Para la busqueda funciona como lo indica el pdf, es decir, se indica el albumId y el permiso "L", "E" o "L,E" y buscara los usuarios que cumplan con la condicion dada.

La aplicacion se levanta por el puerto 8084 del localhost.
Los metodos expuestos estan documentados con Swagger, por lo tanto despues de levantar el proyecto ejecutando la clase PermissionApplication.java o en su defecto instalando la aplicacion con la consola de maven, se podra acceder a la url http://localhost:8084/swagger-ui.html donde se encontraran todos los metodos que contiene el api.

# PrincipalService

En este proyecto se encuentra la primera parte del WChallenge que se encarga de hacer las busquedas de usuarios, fotos, y los albumes.

La aplicacion se levanta por el puerto 8083 del localhost.
Los metodos expuestos estan documentados con Swagger, por lo tanto despues de levantar el proyecto ejecutando la clase WChallengeApplication.java o en su defecto instalando la aplicacion con la consola de maven, se podra acceder a la url http://localhost:8083/swagger-ui.html donde se encontraran todos los metodos que contiene el api.

# Notas
Los servicios fueron realizados con spring boot, Java 8.
