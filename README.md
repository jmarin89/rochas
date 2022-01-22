ABOUT
--------

Rochas

INSTALLATION
--------

En el directorio del proyecto usa el comando "gulp" con el terminal en el que se tenga instalado.

Si tienes problemas de compatiblidad :

 - Crea un archivo "npm-shrinkwrap.json" con el siguiente contenido :
 

    {
      "dependencies": {
        "graceful-fs": {
            "version": "4.2.2"
         }
      }
    }


 - Usa "npm install" para actualizar el "npm-shrinkwrap.json".
 - Vuelve a usar el comando "gulp" para inicializar el proyecto.

GIT
--------

https://github.com/jmarin89/rochas