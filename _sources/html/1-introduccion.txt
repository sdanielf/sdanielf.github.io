Introducción
============

Conceptos básicos sobre la internet
-----------------------------------

La internet es una red global de computadoras que permite transmitir
datos y servicios. Las computadoras que ofrecen servicios se denominan
*servidores* y las que los utilizan son *clientes*.

En esta comunicación cliente-servidor, el cliente envía al servidor
mensajes llamados *peticiones*, el servidor al recibirlas las procesa y
por cada petición devuelve una *respuesta*.

La aplicación que se utilizan los clientes para acceder a los sitios web,
se llama *navegador web*, el mismo permite ingresar la dirección de
un servidor, realiza peticiones al mismo y las interpreta para dibujar
en pantalla una página web.

URI: Identificador de Recursos Uniforme
---------------------------------------

Para realizar cualquier petición a un servidor, se necesita un texto
llamado URI. Este contiene:

* *Protocolo* (ej: http, https, ftp)
* *Dirección del servior* (nombre o número de IP)
* Número de *puerto* en el servidor

  * Cuando no se especifica en HTTP es el 80
* *URL* (dirección del recurso dentro del servidor)
* Usuario y contraseña (en servidores protegidos)

Ejemplos de URIs
^^^^^^^^^^^^^^^^

+-----------+------------------------+--------+-------------------+
| Protocolo | Dirección del servidor | Puerto | Dirección interna |
+===========+========================+========+===================+
| http://google.com/                                              |
+-----------+------------------------+--------+-------------------+
| http      | google.com             | 80     | /                 |
+-----------+------------------------+--------+-------------------+
| https://es.wikipedia.org/wiki/Uruguay                           |
+-----------+------------------------+--------+-------------------+
| https     | es.wikipedia.org       | 80     | /wiki/Uruguay     |
+-----------+------------------------+--------+-------------------+

La formas general de un url es::

  protocolo://maquina/direcotio.archivo

Incluyendo más información puede llegar a quedar::

  protocolo://usuario:contraseña@máquina:puerto/directorio.archivo

El formato HTML
---------------
Los servidores web al recibir una petición deben devolver un archivo.
Cuando el cliente pide una página web se devuelve un archivo de texto
que contiene una descripción de la página en un lenguaje similar al
que utilizamos para comunicarnos.

HTML significa `Hyper Text Markup Language`, los archivos escritos
en este lenguaje tienen como extensión `.html` o `.htm`. La causa de la
segunda es que en los antiguos sistemas operativos los archivos solo
podían tener extensiones de 3 caracteres.

La W3C estandariza las reglas del lenguaje HTML de acuerdo a como
evoluciona la web y sus necesidades. A partir de esta especificación cada
navegador web utilza su propio intérprete para comprender estos archivos y
representarlos en pantalla.

Resumen gráfico
---------------

.. figure:: img/http-protocolo-peticion.png

  Extraido de `hermosaprogramacion.com <http://www.hermosaprogramacion.com/2015/01/android-httpurlconnection/>`_
