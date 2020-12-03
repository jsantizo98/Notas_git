# Git ignore
Funciona de tal forma que evita extenciones o nombres de archivos para esto se crea un archivo .gitignore el cual por defecto lo reconce git
* Ignorar todos los archivos
    * *.txt
* Hace un excepcion con archivos con extensiones que ya fueron ignorardas
    * !prueba.txt
* Ignora toda una carpeta pero no subcarpetas
    * /nombre_carpeta
* Ignora toda una carpeta y subcarpetas
    * nombre_carpeta
* Ignora un tipo de archivo especifio en una carpeta especifica
    * carpeta/*.txt
    * carpeta/prueba.txt
* Ignora todos los archivos .pdf en la carpeta y subcarpeta
    * carpeta/**/*.pdf
* Ignora varias extensiones de archivos que terminen en o y/o a
    *.[oa]