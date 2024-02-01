# Aquí están los pasos básicos que seguirías en la línea de comandos de Git:

Verificar la Rama Actual:
Antes de crear una nueva rama, es una buena práctica verificar en qué rama te encuentras actualmente. Esto se hace con:
git branch

Crear una Nueva Rama:
Supongamos que quieres añadir una nueva función llamada "Modulo-1". Crearías una nueva rama así:

git branch Modulo-1

Cambiar a la Nueva Rama:

git checkout nueva-funcion

A partir de este punto, cualquier cambio que realices estará en la rama "nueva-funcion" y no afectará a la rama "master/main".

Realizar Cambios en tu Código:
Aquí es donde escribes el código de tu nueva función o realizas los cambios deseados.

Añadir y Confirmar los Cambios:
git add .
git commit -m "Añadida nueva función"

Fusionar la Rama con Master/Main:
git checkout master
Y fusionas la rama "Modulo-1" con "master/main":
git merge Modulo-1

Eliminar la Rama:
git branch -d Modulo-1
