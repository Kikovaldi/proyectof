# proyectof

proyecto final 3

Este proyecto está creado para el módulo 3 del Curso de Desarrollo de aplicaciones web.

Finalidad

Es un buscador de peliculas sobre una API, enlazado a una base de datos MYSQL para poder grabarlas y tenerlas en local.

Funcionalidad

-Para hacer funcionar el proyecto, hay que tener una base de datos en este caso se ha trabajado con MySQHL workbench.
-Hay que configurar los user, puertos, contraseñas y parámetros para que coincidan con los del archivo config.js
- Al bajarse el repositorio falta la carpeta node_modules, así que con la terminal hay que navegar hasta la capeta del proyecto y usar el comando -> npm install . este comando instala node en el proyecto.
- Una vez se haya instalado node y se tenga configurada la base de datos, con las carpetas correspondientes, podemos hacer un npm run dev en la carpeta del proyecto en la terminal y luego go live del VSC para tener nuestro buscador funcionando desde el local.
- Es posible que haya un error de cors con el navegador así que se recomienda instalar un puglin de cors para chrome u otro navegador que se esté utilizando.

Una vez esté todo hecho hay que ir al go live para ver el buscador en local.

Datos

- Los datos son recogidos de una API mediante un fetch llamada, api.themoviedb.org.
- El repositorio donde está guardado el proyecto es : https://github.com/Kikovaldi/proyectof
- Para cambiar el proyecto de repositorio de git hab hay que seguir los siguientes pasos, una vez hechos al hacer git add, commit push, se subiran a su repositorio. 

- Primeramente debes crear un repositorio vacío en github y copiar el enlace.
- en la terminal en la carpeta del proyecto debemos escribir:
    - git remote remove origin
    - git remote add origin (URL)
    - git branch -M main
    - git push -u origin main
una vez realizado ya esta enlazado con tu proyecto ya puedes proceder con el add commit y push.

Extra

- Como posibles opciones en un futuro se podría incluir unas paginas vistas por género, para poder filtrarlas por ellos.