---
title: Demo
weight: 3
output: hugodown::md_document
rmd_hash: 6fc515810edff908

---

## Recordatorio del último encuentro

Tenemos un paquete con una función.

------------------------------------------------------------------------

## Un *test*

-   `use_testthat()`.

-   `use_test("time")`: primero un *test* simple, luego un *snapshot test*, luego un *snapshot test* del error.

-   [`devtools::test()`](https://rdrr.io/pkg/devtools/man/test.html) o botón.

-   [`devtools::check()`](https://rdrr.io/pkg/devtools/man/check.html)

:eyes: [sitio de testthat](https://testthat.r-lib.org/)

------------------------------------------------------------------------

## Más *tests*

-   Usá [`withr::local_options()`](https://rdrr.io/pkg/withr/man/with_options.html) en un *test*.

-   Mirá la documentación de [`testthat::test_path()`](https://rdrr.io/pkg/testthat/man/test_path.html).

-   Busca una función de ayuda en un archivo `tests/testthat/helper-bla.R` y mira lo que hace. <https://github.com/search?q=user%3Atidyverse+path%3Atests%2Ftestthat+path%3A**%2Fhelper.*&type=code&ref=advsearch>

:eyes: [sitio de withr](https://withr.r-lib.org/)

:eyes: [Código y archivos de ayuda para tus *tests* testthat](https://blog.r-hub.io/2020/11/18/testthat-utility-belt/)

:toolbox: ¡repite los pasos!

------------------------------------------------------------------------

## GitHub Actions

-   `usethis::use_github_action("check-standard")`. `R CMD check` en la nube, diferentes sistemas operativos.

:eyes: [utilizá esta función para configurar las Acciones de GitHub](https://usethis.r-lib.org/reference/github_actions.html)

:toolbox: ¡Repite los pasos!

------------------------------------------------------------------------

