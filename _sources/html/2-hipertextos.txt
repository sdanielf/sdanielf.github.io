Descripción de Hipertextos
==========================

Primeros pasos con HTML
-----------------------

Para escribir una página en lenguaje html, es necesario abrir un editor de
textos y escribir código como el que se muestra a continuación.

.. code-block:: html

  <!DOCTYPE html>
  <html>
    <head>
      <title>Hola mundo</title>
    </head>
    <body>
      Hola Mundo desde HTML
    </body>
  </html>

Al guardar este archivo, hay que asegurarse de que el nombre termine con
extensión `.html` y luego puede abrirse desde un explorador de archivos
haciéndole doble click. Esta acción lo abrirá con un navegador web.

Elementos, etiquetas de inicio y de fin
---------------------------------------

Análizando el código escrito, el lenguaje HTML está formado por etiquetas.
Cada etiqueta tiene un nombre con un significado en el lenguaje HTML.
Las etiquetas permiten describir elementos con la siguiente secuencia.

* Etiqueta de inicio
* Contenido del elemento
* Etiqueta de fin

Para dar inicio a un elemento, debe ponerse el nombre de su etiqueta usando
antes y después del mismo los signos ``<`` y ``>`` respectivamente. Para dar
fin a un elemento se utilizan los caracteres ``</`` antes del nombre y al igual
que para la etiqueta de inicio, se utilizan el caracter ``>``.
Como ejemplo, para el elemento cuya etiqueta se llama body, su inicio se indica
con la siguiente sintaxis::

  <body>


Y la etiqueta de fin::

  </body>

Jerarquia en arbol y significado de las etiquetas
-------------------------------------------------

El contenido del elemento puede ser texto, o contener más elementos dentro,
esto genera entre los diferentes elementos una relación de jerarquía.
En el ejemplo anterior se puede ver un elemento ``title`` que está dentro de un
elemento ``head``, el cual está en un elemento ``html``.

Todo documento en HTML está formado por la siguiente estructura:

* html

  * head

    * title

  * body

Todo el documento está representado por un elemento html. Este se divide en dos
secciones: ``head``, donde se describe información para los navegadores web y
motores de búsqueda (como Google); y ``body``, donde se detalla el contenido de
la página. Dentro de head, el elemento title se trata del título de la ventana
y/o de la pestaña dependiendo del navegador web.

.. figure:: img/hola-mundo-partes.png

En la figura anterior se puede ver el resultado gráfico de abrir el código de
ejemplo en un navegador web y la relación que tiene con los elementos
explicados.

Uso de etiquetas para el formato de texto
-----------------------------------------

