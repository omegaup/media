# omegaUp media

Esta es la estructura que se usa para los art assets:

* 1 carpeta por art asset desde root
* Incluir SVG
* Incluir PNGs en todas las dimensiones necesarias

La carpeta `third_party` es especial: Contiene copias de recursos que no son
propiedad de omegaUp, pero se replican con permiso. Ejemplos:

* evitar hot-linking, en los casos en los que la política de los dueños del
  recurso lo requiera
* tener la necesidad de mostrar el recurso en el modo de lockdown.

En el archivo `third_party/`_`asset`_`/LICENSE.md` debe venir una explicación del
permiso para cada asset.
