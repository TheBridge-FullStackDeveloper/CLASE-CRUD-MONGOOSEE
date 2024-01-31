# Proyecto CRUD con Mongoose

Este es un proyecto básico que utiliza Mongoose para realizar operaciones CRUD (Crear, Leer, Actualizar, Eliminar) en una base de datos MongoDB. 

## Paso 1: Crear un Servidor Express

Lo primero creamos un servidor de express y lo levantamos.


## Paso 2: Conexión DB
Después creamos la conexión de la base de datos a Mongo Atlas.
Para ello un archivo .env que contiene url con la conexión a Mongo Atlas. Después creamos la carpeta config y dentro de ello el archivo config.js con el código que necesitamos para la coneción a la base de datos.

Luego nos importaremos dicha conexión en index.js y llamamos la función para que cuando levantemos el servidor haga la conexión.

## Paso 3: Modelo User
Después creamos el modelo del usuario. Esto permite que podamos realizar operaciones en la base de datos MongoDB relacionadas con la colección de usuarios. Para ello creamos una carpeta models y dentro crearemos nuestros modelos.
En este caso creamos un archivo llamado User.js que contendrá nuestro modelo de User.
De esta forma tendremos una estructura que nos permitirá el uso de operaciones CRUD (Create, Read, Update, Delete) que pueden realizarse en la base de datos.

## Paso 4: Rutas y endpoints
Por último crearemos las rutas y en ellas los diferentes endpoints.

