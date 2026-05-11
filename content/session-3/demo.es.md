---
title: Demo
weight: 3
output: hugodown::md_document
rmd_hash: 4d3db39264c67130

---

## Recordatorio

Tenemos un paquete con una función y *tests*.

Esa función tiene una página de manual local.

------------------------------------------------------------------------

Abre la IDE que querés usar hoy.

**Si usás Positron aqui son paginas de documentación sobre atajos de teclado: [general](https://positron.posit.co/guide-r.html#keyboard-shortcuts), [R](https://positron.posit.co/keyboard-shortcuts.html), [RStudio](https://positron.posit.co/migrate-rstudio-keybindings.html).**

## Documentación

:warning: pkgdown necesita que tu paquete sea *instalado*.

- `install.packages("rmarkdown")`, [`usethis::use_readme_rmd()`](https://usethis.r-lib.org/reference/use_readme_rmd.html), escribir cosas, [`devtools::build_readme()`](https://devtools.r-lib.org/reference/build_readme.html), commit+push, mirar el repositorio de GitHub.

- `usethis::use_vignette("minipkg.qmd")` (Quarto) o `usethis::use_vignette("minipkg")` (R Markdown), escribí cosas. Viñeta != artículo.

- `install.packages("pkgdown")`, [`usethis::use_pkgdown()`](https://usethis.r-lib.org/reference/use_pkgdown.html), [`pkgdown::build_site()`](https://pkgdown.r-lib.org/reference/build_site.html). Localmente.

:eyes: [pkgdown sitio web](https://pkgdown.r-lib.org/)

:toolbox: ¡Repetí los pasos!

## Construir el sitio web automáticamente

- [`usethis::use_pkgdown_github_pages()`](https://usethis.r-lib.org/reference/use_pkgdown.html) cambia la configuración de las páginas GitHub del repositorio, añade la URL a la configuración pkgdown y a DESCRIPTION.

:eyes: [usá esta función para configurar las Acciones de GitHub](https://usethis.r-lib.org/reference/github_actions.html)

:toolbox: ¡Repetí los pasos!

------------------------------------------------------------------------

