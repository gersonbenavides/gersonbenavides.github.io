+++
date = "2021-01-05T00:00:00-05:00"
title = "La plataforma de desarrollo GLib/GTK"
description = "Una guía de introducción a GLib/GTK."
slug = "glib-gtk-libro"
draft = false

[taxonomies]
    categories = ["projects"]
    tags = ["glib", "gtk", "book"]

[extra]
    page_identifier = "projects-glib-gtk-libro"
+++

Esta es una traducción al español del libro *The GLib/GTK Development Platform – A Getting Started Guide*.

<!-- more -->

<div class="my-3 text-center">
<img src="https://raw.githubusercontent.com/gersonbenavides/glib-gtk-libro/main/mdbook/src/assets/img/logo-gtk.svg" alt="Logo de GTK" title="GTK"  width="40%">
</div>


## Libro en LaTeX

Puede descargar la versión estable del libro [La plataforma de desarrollo GLib/GTK: Una guía de introducción](https://raw.githubusercontent.com/gersonbenavides/glib-gtk-libro/main/glib-gtk-libro.pdf) en formato PDF o puede realizar la compilación de la versión en desarrollo usted mismo escribiendo:

```bash
$ cd latex
```

```bash
$ latexmk -pdf main.tex
```

## Libro web

Actualmente se esta trabajando en una versión [web](https://gersonbenavides.github.io/glib-gtk-libro/) del libro, puede ver su estado en la ruta `mdbook/` del proyecto.

```bash
$ cd mdbook
```

```bash
$ mdbook build
```


## Contribución

Si desea contribuir con el desarrollo de este libro puede apoyar con:

* **Soporte en redacción**: Escribiendo o revisando el texto, para hacerlo participe en el repositorio del libro (<https://github.com/gersonbenavides/glib-gtk-libro>) dando su opinión o desarrollando las tareas propuestas (revise el archivo TODO).

* **Soporte financiero**: El libro se publica como un documento *libre* y es gratuito. Pero no se materializa en un espacio vacío, se necesita tiempo para escribir. Al donar, demuestra su aprecio por este trabajo y ayuda a su desarrollo futuro. Puede encontrar un botón de donación en <https://gersonbenavides.github.io/>.

[![Liberapay](https://img.shields.io/badge/Financia%20mi%20trabajo-F6C915?style=flat&logo=liberapay&logoColor=ffffff "Finance my work")](https://liberapay.com/gersonbenavides/donate)  [![PayPal](https://img.shields.io/badge/Realiza%20una%20donación-00457C?style=flat&logo=paypal "Make a donation")](https://paypal.me/gersonbdev?country.x=CO&locale.x=es_XC)


¡Gracias!


## Créditos

[Sitio web del proyecto oficial](https://people.gnome.org/~swilmet/glib-gtk-book/).


## Licencia

<div class="my-3 text-center">
<img src="https://gersonbenavides.github.io/glib-gtk-libro/assets/img/license-cc-by-sa-88x31.png" alt="CC BY-SA 4.0 license" title="Attribution-ShareAlike 4.0 International"  width="88px">
</div>

Este trabajo está autorizado bajo una licencia internacional Creative Commons Attribution-ShareAlike 4.0:

<https://creativecommons.org/licenses/by-sa/4.0/>

Algunas secciones están basadas en el libro *GTK+/Gnome Application Development*, escrito en 1999, editado por New Riders Publishing y con licencia de Open Publication License. La última versión de la licencia de publicación abierta se puede encontrar en:

<http://www.opencontent.org/openpub/>