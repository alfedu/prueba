# Ejercicio 3
Tenemos el siguiente proyecto de gestión de tareas implementado en Java 1.8. 
La ejecución del JAR se realiza de la forma habitual. Esto es, si el JAR se llamase mijar-1.0.0.jar, se ejecutaría ``java -jar mijar-1.0.0.jar``.

Una vez ejecutado y cargado el servidor web, se puede acceder al API en la URL: ``http://localhost:8080/tasks``.

Se pide:

1. Realizar la construcción automática con Travis incluyendo el fichero de configuración correspondiente.     
2. Configura Travis CI para que envíe un correo siempre que haya una nueva build, sólo en caso de error.
3. Modifica el fichero de configuración de Travis para que construya el proyecto en Oracle JDK 7 y Oracle JDK 8.
4. (Extra) Finalmente, realice los pasos necesarios para desplegar el proyecto de manera automática en Heroku a través de Travis. Incluya la url del despliegue de la aplicación en el fichero README.md del proyecto.
