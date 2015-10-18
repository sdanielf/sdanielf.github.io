Introducción
============

Código de máquina
-----------------

El componente de la computadora encargado de ejecutar instrucciones es el
microprocesador. Toda la información que pasa por él llega representada en
forma eléctrica, se utiliza un valor alto de corriente y un valor bajo,
para esto la información se guarda en *código binario* (de ceros y unos).

Las primeras computadoras disponían de un enorme panel de conectores donde
cada cable insertado representaba un uno y cada cable desconectado un cero.
Cada computadora tenía su propio lenguaje binario, por lo que los
programadores comenzaron a diseñar sus programas en papel en un lenguaje
más facil de entender entre los humanos para luego poder traducir esas
instrucciones al código de máquina.

El uso del papel para escribir un programa de forma entendible para los
humanos dio lugar a lo que hoy conocemos como *pseudocódigo*. Hasta el
día de hoy a la hora de resolver problemas complejos se recomienda
escribir en un papel los pasos para resolver el problema y luego traducirlos
al lenguaje de programación que se desee.

Lenguaje ensamblador
--------------------

Para facilitar el trabajo de los programadores se diseñó un lenguaje preciso
con el que a través de un archivo de texto pueden escribirse instrucciones
directas al procesador, luego un programa denominado *ensamblador* traduce este
archivo a código de máquina y genera un programa que sí puede ser ejecutado
por el procesador.

El lenguaje ensamblador al representar instrucciones directas en el procesador
es completamente distante del pseudocódigo que un programador puede escribir
al buscar la solución a un problema. Es por esto que se crearon nuevos
lenguajes que funcionan con menos problemas de compatibilidad entre equipos
y cada vez más parecidos al pseudocódigo.

Clasificación general de los lenguajes de programación
------------------------------------------------------

Alto o bajo nivel
^^^^^^^^^^^^^^^^^

Un lenguaje de alto nivel es aquel que se acerca al lenguaje natural de los
humanos y a los problemas que le interesa resolver a los humanos. Por
el contrario, cuanto más bajo sea el nivel de un lenguaje, al escribir va se
hace necesario ser preciso en instrucciones que le importan al procesador y
a las memorias de la computadora para funcionar.

Los lenguajes de bajo nivel ofrecen como ventaja un altísimo rendimiento
mientras que los lenguajes de alto nivel se caracterizan por ser más lentos,
pero ofrecen una mayor legibilidad, permiten organizar mejor el código
lo cual se convierte en programas con menos errores.

Luego del código de máquina y el lenguaje ensamblador, uno de los lenguajes
de programación de más bajo nivel es C. Python por otro lado se denomina
lenguaje de muy alto nivel, la sintaxis del lenguaje suele compararse con el
pseudocódigo y está recomendado dentro de los lenguajes que pueden usarse
para aprender a programar.

Compilado o interpretado
^^^^^^^^^^^^^^^^^^^^^^^^

Así como el ensamblador era un programa que traducía el código en este lenguaje
al código de máquina, cada máquina tenía su propio lenguaje ensamblador.

Con los lenguajes de programación modernos, se le comenzó a llamar *código
fuente* a los archivos que el programador escribe en un lenguaje de
programación. Al proceso de pasar *código fuente* a *código de máquina*
se le llamó *compilación*, por lo tanto el programa que lo hace se llama
*compilador*. El proceso de compilación no se explicará con profundidad en
este capítulo.

En los lenguajes interpretados, en lugar de traducirse el código fuente a
código de máquina para luego distribuir el código de máquina a los usuarios,
se necesita de un programa llamado intéprete que en cada ejecución del
programa se encargue de leer el archivo de código fuente y enviar las
instrucciones en tiempo real a la computadora.

Python es un lenguaje interpretado, la implementación más utilizada es
CPython, el cual es un intérprete de Python escrito en lenguaje C.
Se puede hablar de Python para referirse a CPython, pero existen otras
implementaciones menos utilizadas como Jython en Java.

Instalación del intérprete de Python
------------------------------------

Se buscará que los ejemplos de código funcionen en Python 3.4 o versiones
más recientes.

* En los sistemas Linux se recomienda buscar información específica para
  la distribución que se esté utilizando. Muchas veces el intérprete ya
  viene instalado en el sistema por defecto.
* En Windows, se puede 
  `descargar el instalador <https://www.python.org/downloads/windows/>`_ .
* En Mac OS X:
  `página de descargas <https://www.python.org/downloads/mac-osx/>`_ .
