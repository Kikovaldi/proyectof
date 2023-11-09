# Proyecto Final 3 - Buscador de Películas

Este proyecto ha sido creado como parte del módulo 3 del Curso de Desarrollo de Aplicaciones Web. Su objetivo es desarrollar un buscador de películas que utiliza una API para obtener datos, los almacena en una base de datos MySQL y permite visualizarlos localmente.

## Finalidad

El propósito de este proyecto es implementar un buscador de películas que interactúa con una API de `api.themoviedb.org` para obtener información sobre películas. Los datos se almacenan en una base de datos MySQL y se pueden gestionar localmente.

## Funcionalidad

Para ejecutar el proyecto, sigue estos pasos:

1. Configuración de la base de datos:
   - Se requiere una base de datos MySQL. Se recomienda el uso de MySQL Workbench.
   - Ajusta los parámetros de usuario, puertos, contraseñas y otros detalles en el archivo `config.js` para que coincidan con la configuración de tu base de datos.

2. Preparación del entorno:
   - Es probable que la carpeta `node_modules` esté ausente al descargar el repositorio. En la terminal, navega hasta la carpeta del proyecto y ejecuta el comando:
     ```
     npm install
     ```
     Esto instalará las dependencias de Node necesarias para el proyecto.

3. Iniciar el buscador:
   - Una vez instaladas las dependencias y configurada la base de datos, ejecuta el comando en la terminal:
     ```
     npm run dev
     ```
   - Luego, utiliza la extensión "Go Live" de Visual Studio Code para acceder al buscador localmente.

4. Nota sobre CORS:
   - Puede haber un error de CORS al utilizar el buscador en el navegador. Se recomienda instalar un plugin de CORS en tu navegador (por ejemplo, una extensión para Chrome u otro navegador).

## Datos

- Los datos son obtenidos de la API `api.themoviedb.org` mediante una solicitud Fetch.
- Repositorio del proyecto: [Enlace al repositorio](https://github.com/Kikovaldi/proyectof)

## Cambio de Repositorio Git

Si deseas cambiar el repositorio de Git para este proyecto, sigue estos pasos:

1. Crea un repositorio vacío en GitHub y copia su enlace.
2. En la terminal, dentro de la carpeta del proyecto, ejecuta los siguientes comandos:

git remote remove origin
git remote add origin <URL_del_nuevo_repositorio>
git branch -M main
git push -u origin main


Una vez completado, el repositorio estará enlazado con tu nuevo proyecto y podrás continuar con `add`, `commit` y `push`.

## Posibles Mejoras

Como futuras opciones de desarrollo, se podría considerar la implementación de páginas vistas por género, lo que permitiría filtrar las películas por categorías.

