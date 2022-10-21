---
title: "RecordarHugo"
date: 2022-10-18T16:27:03-03:00
draft: true
---

En formato yaml no se permite tabulaciones. Posiblemente en formato toml tampoco.
Esto me estuvo retrasando mucho en todo.
Quiz�s este fue el problema en el men� en toml.
:(

Increíble, pero los pares key: values , en especial el de imágenes parecen estar definidos por el tema.
En el caso de ananke featured_image: "" (funcionó en yml sin comillas) en archetipes/default.
Revisar en cada caso la documentación del tema cada vez que cambie.

#commando para garantizar la reconstrucción del sitio:
hugo server --disableFastRender --noHTTPCache -D

REFERENCIAS DE MARKDOWN  
https://www.markdownguide.org/basic-syntax/