---
title: "Recordar en Draft"
date: 2022-09-23T15:05:22-03:00
draft: true
---

Este archivo no debería verse en Netlify, sólo en local Hugo server -D

Primero. Es absolutamente necesario en git al clonar usar "--recurse-submodules ..." sino tira error de falta de archivos. Posiblemente lo requiera pull cuando modifique el tema y sólo funcione con comando; "git submodule update --init --recursive". 
Según esta página: https://github.blog/2016-02-01-working-with-submodules/

También dicho así:
Es absolutamente necesrio [ git clone --recurse-submodules ...] para clonar el repositorio de github
porque sino tira el error "no layout file for "HTML" for kind "home""
https://discourse.gohugo.io/t/no-layout-file/38408/5


Para git-cmd portable es necesario agregar path para git-cmd:
path %PATH%;C:\Users\juan.nagy\Hugo

Para git-bash aregar el ejecutable y los archivos de hugo en la carpeta: bin de Mingw32
Que es de ahí de donde toma los programas auxiliares. Sino, investigar cómo agregarlo con variable de entorno.


cambiar el nombre del branch a "main" con GIT para que lo acepte mejor github


notar que con git-bash  capaz que funciona así, sino git cmd, usar así
Thanks everyone - it works. In config.toml, I had to replace
theme = \ "ananke\ " by theme = “ananke”

Es decir:
Recordar en el tutorial está escrito para linux, y usa caracter de escape para escribir las comillas, que son caracteres especiales. En este caso, en vez de ser [theme = \ "ananke\ "] es [theme = “ananke”].



Set your username:


git config --global user.name "FIRST_NAME LAST_NAME"

Set your email address:
git config --global user.email "MY_NAME@example.com"

Para ver git config user.name
y user.mail

GIT no sube carpetas vacías. En el caso de HUGO principalmente son: data, layouts, static
Meterle un archivito vacío con cualquier nombre para que conserve estructura de carpetas si fuese necesario.
(en caso de que el server no pueda crearlos automáticamente.).


Palabras sagradas:

git clone --recurse-submodule ... ..
git config --global user.mail "" y user.name ""
git remote origin -u
git branch name change
gti pull
git status
git add -A
git commit -m "mensaje cortito"
git push