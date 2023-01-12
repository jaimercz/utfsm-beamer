# Plantilla (beamer) para presentaciones UTFSM
Plantilla para *beamer* que sigue las instrucciones del manual corporativo de la Universidad Técnica Federico Santa María (Chile) ([www.usm.cl](http://www.usm.cl)).

![MacDown Screenshot](figures/thumbnail.png)

Podría interesarle:

- [Plantilla Latex para Memorias y Tesis](https://github.com/jaimercz/utfsm-thesis): Plantilla para la creación de Memorias de la UTFSM.
- [Plantilla Latex (exam) para Certámenes](https://github.com/jaimercz/utfsm-exam): Plantilla (basada en `exam`) con formatos para la UTFSM.

 
## Uso de la Plantilla

Simplemente ajuste los parámetros para la portada del archivo `beamer.tex` y edite el archivo `frames.tex` que contiene las transparencias (*frames*).

Para compilar la bibliografía, recuerde

```zsh
$ pdflatex beamer & biber beamer & pdflatex beamer & pdflatex beamer

```

**Nota**: esta versión hace uso de `biber` y no `bibtex/natbib`.

### Overleaf (y otros)

Esta versión ha sido probada con editores en línea como [Overleaf](https://overleaf.com), Authorea, y Papperia.

## Licencia
El uso esta permitido bajo la licencia [*MIT*](https://opensource.org/licenses/MIT). (Significa que puede ocuparla/modificarla, pero debe mantener la referencia al autor.)

**Importante:** Se excluyen de esta licencia los archivos de imágenes. Todas las imágenes son propiedad intelectual de la UTFSM &copy;.

## Contribuciones
Por favor, directamente a través de un `pull request`.

O, puedes dejar un comentario en la sección [Issues](https://github.com/jaimercz/utfsm-beamer/issues).
