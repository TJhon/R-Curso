
R-Curso
=======

Fecha actualizada: 2020-08-08

Descripcion: Algunos recursos para el aprendizaje de R

------------------------------------------------------------------------

Este es un repositorio para aprender algo de R y recomendaciones que
encontre a lo largo del camino del aprendizaje de este lenguaje de
programacion.

Este curso esta un poco sesgado al uso de windows para todos los
procesos, aunque muchos de estos no difieren mucho de Linux y Mac.

Lo videos relacionados esta presentes en:

-   [Vision general y
    usos](https://www.youtube.com/playlist?list=PLDVZfi7ztrg5RU6xmgceV4MJ9YlE7oele)
-   [Solo
    R](https://www.youtube.com/playlist?list=PLDVZfi7ztrg6Ob825jQ6AEYGUceKHg_fY)

Antes de iniciar - Instalaciones Mediante `chocolatey`
------------------------------------------------------

**Chocolatey** para windows 10

1.  Abrir powershell (Como administrador)
2.  Ejecutar el siguiente codigo

-   Set-ExecutionPolicy Bypass -Scope Process -Force;
    *S**y**s**t**e**m*.*N**e**t*.*S**e**r**v**i**c**e**P**o**i**n**t**M**a**n**a**g**e**r*
    ::SecurityProtocol =
    *S**y**s**t**e**m*.*N**e**t*.*S**e**r**v**i**c**e**P**o**i**n**t**M**a**n**a**g**e**r*
    ::SecurityProtocol -bor 3072; iex ((New-Object
    System.Net.WebClient).DownloadString(‘<a href="https://chocolatey.org/install.ps1" class="uri">https://chocolatey.org/install.ps1</a>’))

**Solo hacer lo siguiente** si confias en mi (entonces proceder a abrir
mediante Rstudio y correr el documento `config.r` :

`choco install git pandoc r r.studio rtools -y`

**Git**

    `choco install git -y`

-   [Ver
    videos](https://www.youtube.com/playlist?list=PLmUnyBCRHkvUPkrsseI1SmMtYgfc-f8Kn)
    -   Opcional

**R y Rstudio**

`choco install r -y`

`choco install r.studio -y`

`choco install rtools -y` Opcional

**Paquetes iniciales**

Ver y correr `config.r`

Se aceptan recomendaciones
==========================

Para poder modificar, corregir, recomendar o cualquier otra cosa, para
ello seguir los siguientes pasos y guiarse de la siguiente captura de
pantalla:

![](fig/recomendaciones.png) 1. Crear una cuenta de GitHub (en la parte
superior derecha) 1. Ir al [link](https://github.com/TJhon/r-curso) del
curso. - Dar click en `Issues`, para problemas con el curso o
recomendaciones. - `Pull requests` para modificaciones dentro del
repositorio

Indice
======

Para una vision general ir al
[indice](https://github.com/TJhon/r-curso/blob/master/Indice.md)

Archivos
========

Esta es la lista de archivos creados hasta la fecha de actualizacion, es
proposito: es la simplificacion de busqueda de archivos dentro del
repositorio.

    fs::dir_tree()

    ## .
    ## +-- config.r
    ## +-- fig
    ## |   \-- recomendaciones.PNG
    ## +-- Git tips.md
    ## +-- Indice.md
    ## +-- Indice.rmd
    ## +-- notebooks
    ## |   +-- 00-rmarkdown.docx
    ## |   +-- 00-rmarkdown.pdf
    ## |   +-- 00-rmarkdown.rmd
    ## |   +-- 01 - primer.rmd
    ## |   +-- fig
    ## |   |   +-- 00configr.jpg
    ## |   |   \-- test.pdf
    ## |   \-- word
    ## |       \-- none.docx
    ## +-- presentaciones
    ## |   +-- 00instalacion.pdf
    ## |   +-- 00instalacion.rmd
    ## |   +-- 01Rstudio01pasos.html
    ## |   +-- 01Rstudio01pasos.pdf
    ## |   +-- 01Rstudio01pasos.rmd
    ## |   +-- 01Rstudiocuestiones.pdf
    ## |   +-- 01Rstudiocuestiones.rmd
    ## |   +-- 02Rstudiocode.pdf
    ## |   +-- 02Rstudiocode.rmd
    ## |   +-- 02Rstudiorecomendaciones.pdf
    ## |   +-- 02Rstudiorecomendaciones.rmd
    ## |   +-- 03Rintro.pdf
    ## |   +-- 03Rintro.rmd
    ## |   +-- 03Rsimple.pdf
    ## |   +-- 03Rsimple.rmd
    ## |   +-- 03tidyR.rmd
    ## |   +-- 04import.rmd
    ## |   +-- 05visual.pdf
    ## |   +-- 05visual.rmd
    ## |   +-- complementarios
    ## |   |   +-- gracias.rmd
    ## |   |   \-- set.rmd
    ## |   +-- imagenes
    ## |   |   +-- 00configr.jpg
    ## |   |   +-- 01comp.PNG
    ## |   |   +-- 02rstudio.PNG
    ## |   |   +-- 02rstudio1.PNG
    ## |   |   +-- 03config.PNG
    ## |   |   +-- 03config1.PNG
    ## |   |   +-- 03config2.PNG
    ## |   |   +-- 03Packages-tidy.PNG
    ## |   |   +-- 03Packages.PNG
    ## |   |   +-- 04entorno.png
    ## |   |   +-- 04proy.png
    ## |   |   +-- 05git.PNG
    ## |   |   +-- 05git1.PNG
    ## |   |   +-- 05git2.PNG
    ## |   |   +-- 06datos.PNG
    ## |   |   +-- 06datos0.PNG
    ## |   |   +-- 07here.png
    ## |   |   +-- me.png
    ## |   |   +-- notebook.PNG
    ## |   |   \-- Rmarkdown.PNG
    ## |   +-- libs
    ## |   |   +-- font-awesome-5.1.0
    ## |   |   |   +-- css
    ## |   |   |   |   +-- all.css
    ## |   |   |   |   \-- v4-shims.css
    ## |   |   |   \-- webfonts
    ## |   |   |       +-- fa-brands-400.eot
    ## |   |   |       +-- fa-brands-400.svg
    ## |   |   |       +-- fa-brands-400.ttf
    ## |   |   |       +-- fa-brands-400.woff
    ## |   |   |       +-- fa-brands-400.woff2
    ## |   |   |       +-- fa-regular-400.eot
    ## |   |   |       +-- fa-regular-400.svg
    ## |   |   |       +-- fa-regular-400.ttf
    ## |   |   |       +-- fa-regular-400.woff
    ## |   |   |       +-- fa-regular-400.woff2
    ## |   |   |       +-- fa-solid-900.eot
    ## |   |   |       +-- fa-solid-900.svg
    ## |   |   |       +-- fa-solid-900.ttf
    ## |   |   |       +-- fa-solid-900.woff
    ## |   |   |       \-- fa-solid-900.woff2
    ## |   |   \-- header-attrs-2.3
    ## |   |       \-- header-attrs.js
    ## |   +-- moi1.css
    ## |   \-- pdf.r
    ## +-- r-curso.Rproj
    ## +-- README.md
    ## +-- README.rmd
    ## +-- Rstudio-tips.md
    ## +-- scripts
    ## |   +-- 00shortcuts.r
    ## |   +-- 02import.r
    ## |   \-- prueba.r
    ## \-- sumatrapdf
    ##     +-- sumatra-config-night.txt
    ##     \-- sumatra-config.txt
