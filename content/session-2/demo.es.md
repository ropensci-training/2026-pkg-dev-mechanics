---
title: Demo
weight: 3
output: hugodown::md_document
rmd_hash: ec4a60b7391ade3f

---

## Recordatorio del último encuentro

Tenemos un paquete con una función.

------------------------------------------------------------------------

Abre la IDE que querés usar hoy.

**Si usás Positron aqui son paginas de documentación sobre atajos de teclado: [general](https://positron.posit.co/guide-r.html#keyboard-shortcuts), [R](https://positron.posit.co/keyboard-shortcuts.html), [RStudio](https://positron.posit.co/migrate-rstudio-keybindings.html).**

## Un *test*

- `use_testthat()`.

- `use_test("time")`: primero un *test* simple, luego un *snapshot test*, luego un *snapshot test* del error.

- [`devtools::test()`](https://devtools.r-lib.org/reference/test.html) o [Ctrl + Shift + T](https://positron.posit.co/guide-r.html#keyboard-shortcuts).

- [`devtools::check()`](https://devtools.r-lib.org/reference/check.html) o [Ctrl + Shift + E](https://positron.posit.co/guide-r.html#keyboard-shortcuts).

:eyes: [sitio de testthat](https://testthat.r-lib.org/)

------------------------------------------------------------------------

## Más *tests*

- Usá [`withr::local_options()`](https://withr.r-lib.org/reference/with_options.html) en un *test*.

- Mirá la documentación de [`testthat::test_path()`](https://testthat.r-lib.org/reference/test_path.html).

- Busca una función de ayuda en un archivo `tests/testthat/helper-bla.R` y mira lo que hace. <https://github.com/search?q=user%3Atidyverse+path%3Atests%2Ftestthat+path%3A**%2Fhelper.*&type=code&ref=advsearch>

:eyes: [sitio de withr](https://withr.r-lib.org/)

:eyes: [Código y archivos de ayuda para tus *tests* testthat](https://blog.r-hub.io/2020/11/18/testthat-utility-belt/)

:toolbox: ¡repite los pasos!

------------------------------------------------------------------------

## GitHub Actions

- `usethis::use_github_action("check-standard")`. `R CMD check` en la nube, diferentes sistemas operativos.

:eyes: [utilizá esta función para configurar las Acciones de GitHub](https://usethis.r-lib.org/reference/github_actions.html)

:toolbox: ¡Repite los pasos!

------------------------------------------------------------------------

