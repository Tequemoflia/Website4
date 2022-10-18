---
title: "Misegundopost"
date: 2022-09-22T17:19:12-03:00
draft: false
---


En este día en este repositorio y global se cambio el nombre de usuario de git y mail.
Hacerlo así de ahora en mas. Ademas agrega otro post para probar y ademas

Esta carpeta es prueba4 en minseg


RECORDAR:

Es absolutamente necesario [ git clone --recurse-submodules ...] para clonar el repositorio de github
porque sino tira el error "no layout file for "HTML" for kind "home""
https://discourse.gohugo.io/t/no-layout-file/38408/5

GIT no sube carpetas vacías. En el caso de HUGO principalmente son: data, layouts, static

Meterle un archivito vacío con cualquier nombre para que conserve estructura de carpetas si fuese necesario.
(en caso de que el server no pueda crearlos automáticamente.).

Para usar GIT portable es necesario agregar variable de entorno:
path %PATH%;C:\Users\juan.nagy\Hugo

Recordar cambiar el nombre de la rama a main.

Recordar en el tutorial está escrito para linux, y usa caracter de escape para escribir las comillas, que son

caracteres especiales. En este caso, en vez de ser [theme = \ "ananke\ "] es [theme = “ananke”].

Open the command line.

Set your username:
git config --global user.name "FIRST_NAME LAST_NAME"

Set your email address:
git config --global user.email "MY_NAME@example.com"


Recordar

Recordar

git init o git clone --recurse-submodules

git status

git add -A

(-A mayuscula, o agregar un solo archivo indicando)

git commit -m

git remote origin -u direccion

git branch
(tener en cuenta master a main)

git push

git pull
(cuando no se use clone y con seguridad sepa que es la correspondiente)
