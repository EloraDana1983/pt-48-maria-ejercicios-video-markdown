# Ejercicio Checkout y Diff

En el ejercicio parto de tener dos ramas  
-master  
-rama1

Introducimos **git checkout rama1** para camiar de la rama master donde comenzamos a rama1.  
Introduzco **ls** para ver lo que contiene rama1.  
Volvemos a poner **git checkout master** para volver a posicionarnos el master, vuelvo ha hacer **ls** para ver lo que contiene.

En este repositorio no es dificil ver las diferencias que tiene master y rama1 porque solo son un par de archivos.  
En el caso de trabajar con muchos archivos se haría:

**git diff master rama1** diciendolo que queremos ver la diferencia entre la master y rama1, nos dice que hay un nuevo archivo llamado adios.txt que rama1 tiene.  
Si en vez del anterior orden pusieramos **git diff rama1 master** el resultado es diferente porque es a la inversa, nos dice que ha master le falta un archivo.
