---
title: Demo
weight: 3
output: hugodown::md_document
rmd_hash: 9d347fb6c4a68de4

---

## Recordatorio

Tenemos un paquete con una función y *tests*.

Esa función tiene una página de manual local.

## Documentación

:warning: rmarkdown y pkgdown necesitan que tu paquete sea *instalado*.

-   `install.packages("rmarkdown")`, [`usethis::use_readme_rmd()`](https://rdrr.io/pkg/usethis/man/use_readme_rmd.html), escribir cosas, [`devtools::build_readme()`](https://rdrr.io/pkg/devtools/man/build_rmd.html), commit+push, mirar el repositorio de GitHub.

-   `usethis::use_vignette("minipkg.qmd")` (Quarto) o `usethis::use_vignette("minipkg")` (R Markdown), escribí cosas. Viñeta != artículo.

-   `install.packages("pkgdown")`, [`usethis::use_pkgdown()`](https://rdrr.io/pkg/usethis/man/use_pkgdown.html), [`pkgdown::build_site()`](https://pkgdown.r-lib.org/reference/build_site.html). Localmente.

:eyes: [pkgdown sitio web](https://pkgdown.r-lib.org/)

:toolbox: ¡Repetí los pasos!

## Construir el sitio web automáticamente

-   [`usethis::use_pkgdown_github_pages()`](https://rdrr.io/pkg/usethis/man/use_pkgdown.html) cambia la configuración de las páginas GitHub del repositorio, añade la URL a la configuración pkgdown y a DESCRIPTION.

:eyes: [usá esta función para configurar las Acciones de GitHub](https://usethis.r-lib.org/reference/github_actions.html)

:toolbox: ¡Repetí los pasos!

------------------------------------------------------------------------

