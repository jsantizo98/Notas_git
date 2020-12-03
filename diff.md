# Git diff
Funciona para ver que cambio se han realizado en archivos modificados
- git diff <nombre_archivo>
    - Muestra los cambios realizados comparando el archivo anterior guardado en el disco duro contra lo que acabamos de guardar
+ git diff --staged
    + Muestra los cambios del ultimo commit comparadolo con los que tenemos en staged
+ git diff --cached
    + Realiza los mismo que --staged
**Nota:***Si se utiliza git diff y los archivos ya fueron enviados o guardados con un commit esto no mostrara nada*
