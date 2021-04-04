# WChallenge
El proyecto esta distribuido en un proyecto principal que contiene los dos submodulos que son dos web service independientes.

# PermissionAlbumService
En este proyecto se encuentra la segunda parte del WChallenge que se encarga de gestionar el sistema de permisos para los album

La aplicacion se levanta por el puerto 8084 del localhost.
Los metodos expuestos estan documentados con Swagger, por lo tanto despues de levantar el proyecto ejecutando la clase PermissionApplication.java o en su defecto instalando la aplicacion con la consola de maven, se podra acceder a la url http://localhost:8084/swagger-ui.html se podran ver todos los metodos que contiene el api.

# PrincipalService

En este proyecto se encuentra la primera parte del WChallenge que se encarga de hacer las busquedas de usuarios, fotos, y los albumes.

La aplicacion se levanta por el puerto 8083 del localhost.
Los metodos expuestos estan documentados con Swagger, por lo tanto despues de levantar el proyecto ejecutando la clase WChallengeApplication.java o en su defecto instalando la aplicacion con la consola de maven, se podra acceder a la url http://localhost:8083/swagger-ui.html se podran ver todos los metodos que contiene el api.

# Notas
Los servicios fueron realizados con spring boot, Java 8.
