# MEAN
MEAN (Mongo-Express-Angular-Node) Ejemplo de Aplicación Web 

 

    Instalar Node Js y MongoDB 

    $ curl --silent --location https://rpm.nodesource.com/setup_6.x 

    $ dnf install nodejs 

    $ install gcc-c++ make 

    $ dnf install nodejs npm 

    $ node -v 

    $ npm –v 

/**Instalacion de MongoDB**/ 

    $ dnf install mongodb mongodb-server 

    $ service mongod start 

    $ npm install mongoose 

 

    Descargar el Proyecto 

    https://github.com/DjSystemBPM/MEAN.git 

 

    Poner en funcionamiento el proyecto 

    En la carpeta del proyecto ejecutas el siguiente comando: $ npm install 

    En la carpeta del proyecto inicia el servidor nodejs: $ node server.js 

    Inicia el proyecto en el navegador: http://localhost:8084 

 

Notas: 

    package.json: se indican las librerias del proyecto e informacion del proyecto. 

    server.js: este archivo se configura el puerto donde desplegara nuestro server de nodejs y tambien hacia que base de datos mongo apunta. 

    persona.js: es el modelo de datos que utilizaremos para el API Rest 

    Routes.js: definiremos los endpoints de la API REST y sus acciones. Para hacer un ejemplo lo más completo posible, hemos hecho las 4 tipos de llamadas (Get, Post, Put y Delete). 

    controller.js: escribimos las funciones de cada llamada de la API REST. 

    core.js: será el encargado de hacer la peticiones al API REST y de tener actuaalizados los modelos de datos.
