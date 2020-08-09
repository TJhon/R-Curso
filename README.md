
R-Curso
=======

Fecha actualizada 2020-08-08

Algunos recursos para el aprendizaje de R

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
