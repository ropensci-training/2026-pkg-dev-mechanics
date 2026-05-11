---
title: Demo
weight: 3
output: hugodown::md_document
rmd_hash: 9f8d6e3a83cde64e

---

## Preparación de tu sistema

Abre la IDE que querés usar hoy.

- `.Library`, [`.libPaths()`](https://rdrr.io/r/base/libPaths.html)

- `install.packages("devtools")`. [Capítulo Setup del libro R packages](https://r-pkgs.org/setup.html).

- `install.packages("pak")`.

- [`devtools::has_devel()`](https://pkgbuild.r-lib.org/reference/has_compiler.html)

- [`devtools::dev_sitrep()`](https://devtools.r-lib.org/reference/dev_sitrep.html)

- [`usethis::git_sitrep()`](https://usethis.r-lib.org/reference/git_sitrep.html). [Managing Git(Hub) Credentials](https://usethis.r-lib.org/articles/git-credentials.html); ["Managing GitHub credentials from R, difficulty level linux"](https://blog.djnavarro.net/posts/2021-08-08_git-credential-helpers/).

- usethis y devtools en mi .Rprofile. [`usethis::edit_r_profile()`](https://usethis.r-lib.org/reference/edit.html), qué es un .Rprofile? [usethis setup article](https://usethis.r-lib.org/articles/articles/usethis-setup.html).

La preparación no es divertida!

:toolbox: (sin grupos) ¿Algún problema? :fingers_crossed:

------------------------------------------------------------------------

## Creación de paquete

- `pak::pkg_name_check("minipkg3")`

- `usethis::create_package("../minipkg3")`

{{< figure src="/images/screenshot.png" caption="Captura de pantalla en Positron. Azul oscuro: consola R! Azul claro: nombre del proyecto. Verde: barra de menu, por ejemplo para ver opciones. Rosa: para buscar en archivos del proyecto. Rojo: explorador de archivos. Naranja: aqui puedo yo encontrar Control de Versión porqué haciendo clics lo desplazé de la izquierda hasta la derecha, asi de facil, para que se parezca más a Rstudio." >}}

- [`usethis::edit_r_profile()`](https://usethis.r-lib.org/reference/edit.html)

- [`devtools::check()`](https://devtools.r-lib.org/reference/check.html), [`usethis::use_mit_license`](https://usethis.r-lib.org/reference/licenses.html)

- [`usethis::use_git()`](https://usethis.r-lib.org/reference/use_git.html)

- [`usethis::use_github()`](https://usethis.r-lib.org/reference/use_github.html). Mira al repositorio y su :sparkles: pagina de *issues* :sparkles:.

:eyes: [sitio de usethis](https://usethis.r-lib.org/)

:toolbox: Repite las mismas tareas, enviá el enlace de tu repositorio en el chat!

------------------------------------------------------------------------

## Una primera función

- `usethis::use_r("time")`. Explica qué hace [`sprintf()`](https://rdrr.io/r/base/sprintf.html).

- `devtools::load()`, `what_time()`.

- Añadí un argumento.

- [`devtools::load_all()`](https://devtools.r-lib.org/reference/load_all.html), `what_time()`, `what_time(language = "en")`.

:toolbox: ¡Repetí los pasos!

------------------------------------------------------------------------

## Página del manual

- Insertá el esqueleto roxygen2.

- [`devtools::document()`](https://devtools.r-lib.org/reference/document.html), `?what_time`, muestra el archivo Rd.

- Construye y vuelve a cargar (instalá los paquetes desde la pestaña de construcción de RStudio o "R: Install R Package and Restart R" en Positron), intentá utilizar el paquete desde otra sesión. Instalá desde GitHub.

:eyes: [sitio de roxygen2](https://roxygen2.r-lib.org/)

:eyes: [Libro R Packages, the whole game](https://r-pkgs.org/whole-game.html)

:toolbox: ¡Repetí los pasos!

------------------------------------------------------------------------

## Usá dependencias

- Añadí dos dependencias, `use_package("praise")` y `use_package("rlang")`.

- [`devtools::load_all()`](https://devtools.r-lib.org/reference/load_all.html), `what_time()`, `what_time(language = "en")`.

:toolbox: ¡Repetí los pasos!

------------------------------------------------------------------------

