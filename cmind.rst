Implementación de mastermind® en C: ``cmind.c``
-----------------------------------------------

El `mastermind® <http://es.wikipedia.org/wiki/Mastermind>`__ es un
sencillo e interesante juego de lógica. He hecho mi propia versión en
`C <http://es.wikipedia.org/wiki/C_(lenguaje_de_programación)>`__.

Por si a alguien le interesa, aquí dejo el código. Compila sin problemas
con:

::

    cc cmind.c -o cmind

Y éste es su aspecto en acción:

::

    cpu:  ****
    ---------
    a  !!!  abcd
    b  !?   aabb
    c  !?   cdef
    d |xxxx ----
    e  xxxx ----
    f  xxxx ----
    xxxx ----
    xxxx ----
    xxxx ----
    xxxx ----
    ---------
    vycma: abcf

Lo he subido a github: `cmind <https://github.com/mdomlop/cmind>`__

Espero que te guste. Nada como el encanto de jugar a frikadas como éstas
en una terminal.
