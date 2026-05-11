---
outputs:
- Reveal
title: ¡Desarrolla paquetes!
hidden: true
layout: list
weight: 11
output: hugodown::md_document
countdown: true
rmd_hash: 6482e87bcf38b26f

---

# Desarrollo de paquetes

<div class="highlight">

</div>

<div class="highlight">

{{< figure src="132682.jpeg" alt="Bike in repair room" caption="Foto de [Alexander Dummer en Pexels](https://www.pexels.com/photo/black-road-bicycle-inside-room-132682/)." width="400" >}}

</div>

------------------------------------------------------------------------

## Mis credenciales de desarrollo de paquetes R

-   [Revisión de software por pares de rOpenSci](https://ropensci.org/es/software-review).

-   [Guía de desarrollo de rOpenSci](https://devguide.ropensci.org/es/index.es.html).

-   [blog R-hub](https://blog.r-hub.io).

-   Libro [HTTP testing in R](https://books.ropensci.org/http-testing/) con Scott Chamberlain.

-   Participé en el desarrollo de varios paquetes.

------------------------------------------------------------------------

## ¿Por qué desarrollar un paquete R?

La forma más fácil de compartir código/datos/plantillas R Markdown... con

-   vos (en el futuro),

-   las personas que conocés,

-   y las personas que no conocés.

------------------------------------------------------------------------

## ¿Por qué aprender sobre el desarrollo de paquetes?

[Jon Calder](https://joncalder.co.za/) [explicó](https://github.com/iandurbach/datasci-fi/tree/master/docs/packages/slides)

-   Compartir código (y datos);

-   Para aprovechar las herramientas existentes;

-   Para contribuir a otros paquetes.

------------------------------------------------------------------------

## ¿Quién puede escribir un paquete? ¡VOS!

Susan Johnston [preguntó](https://github.com/susjoh/fibonacci).

-   Podés abrir R o RStudio?

-   Podés instalar un paquete?

-   ¿Escribistes alguna vez una función en R?

-   ¿Podrías *aprender* a escribir una función en R?

**¡Podés escribir un paquete en R!**

------------------------------------------------------------------------

## Recursos sobre funciones (1/2)

-   [Materiales del tutorial de R-Ladies East Lansing de Stephanie Kirmer](https://github.com/rladies-eastlansing/2021-rfunctions#writing-r-functions)

-   [Escribe tus propias funciones de R](https://stat545.com/functions-part1.html), curso stat 545 por Jenny Bryan y The STAT 545 TAs;

-   [Capítulo sobre funciones](https://r4ds.had.co.nz/functions.html) en el libro "R for Data Science" de Garrett Grolemund y Hadley Wickham;

------------------------------------------------------------------------

## Recursos sobre funciones (2/2)

-   [Charla "Fun with Functions](https://zealous-wiles-e22e83.netlify.app/talk/funwithfunctions/) por Kaylea Haynes, R-Ladies Manchester.

-   Capítulo sobre Funciones del libro de la materia [Introducción a la Programación II](https://intro-programacion.netlify.app/07_funciones) de Paola Corrales y Yanina Bellini Saibene.

------------------------------------------------------------------------

## ¿Qué es un paquete?

> Para calmar tus temores, recordá que no es más que una carpeta organizada de una manera específica.

[Traducción de una frase de Sébastien Rochette](https://thinkr.fr/transformer-plusieurs-scripts-eparpilles-en-beau-package-r)

------------------------------------------------------------------------

## Automatización

{{< figure src="automate_meme.jpg" alt="Pequeño monstruo que dice automatizar todas las cosas"  caption="Imagen del meme de [Allie Brosh](https://en.wikipedia.org/wiki/Hyperbole_and_a_Half)"  >}}

------------------------------------------------------------------------

## Automatizar... ¿Cómo?

¿Te acordás de Clippy?

------------------------------------------------------------------------

## Automatizando... ¿Cómo?

Te presento a un Clippy realmente útil, `{usethis}` ¡!

{{< figure src="https://usethis.r-lib.org/reference/figures/logo.png" alt="usa este logo, un robot"  >}}

------------------------------------------------------------------------

## ¿Por qué automatizar? Más fácil para...

Trabajo regular, enseñanza, reproducción de problemas.

<div class="highlight">

{{< figure src="5446296.jpeg" alt="Rueda de bicicleta con herramientas en el piso" caption="Foto de [cottonbro studio en Pexels](https://www.pexels.com/photo/wrench-on-a-ground-5446296/)." width="200" >}}

</div>

------------------------------------------------------------------------

## Objetivos para las tres sesiones

-   Conocer (las mejores :innocent:) herramientas para el desarrollo de paquetes;

-   Aprender que no hay magia, sólo práctica y :sparkles: consejos :sparkles:.

<div class="highlight">

{{< figure src="686230.jpeg" alt="Señal de bicicleta en un carril de bicicletas, con hojas de árbol." caption="Foto de [Cristiana Raluca en Pexels](https://www.pexels.com/photo/white-bicycle-road-sign-686230/)." width="300" >}}

</div>

------------------------------------------------------------------------

## Visita al sitio web

:link: <https://desarrollo-paquetes-basico-2026.netlify.app/>

Diapositivas, notas de la demostración, otros recursos

<div class="highlight">

{{< figure src="3932867.jpeg" alt="Niño pequeño en una bicicleta sin pedales" caption="Foto de [Tatiana Syrikova en Pexels](https://www.pexels.com/photo/anonymous-kid-in-helmet-riding-run-bike-on-pavement-in-countryside-3932867/)." width="200" >}}

</div>

------------------------------------------------------------------------

## Hora del taller :bike:

Alternando entre ver y practicar en las salas de Zoom.

<div class="highlight">

{{< figure src="221237.jpeg" alt="Two bikes parked" caption="Foto de [Pixabay en Pexels](https://www.pexels.com/photo/two-bicycles-parked-upright-221237/)." width="200" >}}

</div>

------------------------------------------------------------------------

## De vuelta del taller

`{usethis}` para todo.

<div class="highlight">

{{< figure src="206040.jpeg" alt="Cycle path sign" caption="Foto de [Nika Dzamashvili en Pexels](https://www.pexels.com/photo/black-and-white-bicycle-road-sign-206040/)." width="400" >}}

</div>

------------------------------------------------------------------------

## `.Rprofile`

Cómo guardar los ajustes de una bicicleta.

¡No tenés que ajustar la altura del asiento cada vez que salgas a dar una vuelta!

------------------------------------------------------------------------

## Dos ruedas siempre girando :bike:

-   Cargando, probando, editando.

-   Ejecutar (añadir) las pruebas, editar. ¡En la próxima sesión!

------------------------------------------------------------------------

## Comprobación R CMD (devtools::check())

<div class="highlight">

{{< figure src="4543112.jpeg" alt="Bike traffic light" caption="Foto de [cottonbro studio en Pexels](https://www.pexels.com/photo/traffic-light-on-red-light-4543112/)." width="300" >}}

</div>

------------------------------------------------------------------------

## ¿Tenés preguntas?

¿Nos vemos en el próximo curso de desarrollo de paquetes?

Prepará las preguntas con antelación, envialas con antelación si podés.

<iframe src="https://giphy.com/embed/XFpCAWSfTwXh2uSEk2" width="480" height="269" frameBorder="0" class="giphy-embed" allowFullScreen></iframe><p><a href="https://giphy.com/gifs/moon-et-extra-terrestrial-XFpCAWSfTwXh2uSEk2">via GIPHY</a></p>

