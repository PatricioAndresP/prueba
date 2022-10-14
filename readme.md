# Ejercicio 1

Crear repo local:

en shell ejecutar:

...
$ git init
...


ejecutar git status
...
$git status
...

agregar archivo a git:
...
$ git add readme.md

Configurar identificacion del desarrollador:
$git config --global user.email "ejemplo@algo.com"
$git config --global user.name "nombre"
...

Hacer primer commit

...
git commit -m "feat agregar archivo readme"
...

despues ejecutar git status

$git status


agregar archivo git ignore con este contenido:

...
env
...

o cualquier cosa que quieran ignorar

...
git commit -a -m "actualizar  con .gitignore y README"

nota: git commit -a es como hacer un add y un commit al mismo tiempo