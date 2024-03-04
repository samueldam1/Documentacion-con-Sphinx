Cabecera
========

Parrafos
--------
Para escribir párrafos solo tenemos que escribir.

Si queremos marcar con *cursiva* usamos **.

**Negrita con doble asterisco**. (****).

Ejemplos de código: ''import os ''

Listas
------
* Listas.
    * Sublista

.. _nivelesSecciones:
Niveles seciones
----------------
Diferentes niveles de seccion se escribrend de la siguiente forma:

* = Secciones.
* = "Secciones".
* '-' Subsecciones.
* ^ Subsecciones.
* " Parrafos

Lista ordenada
^^^^^^^^^^^^^^
1. Primero
2. Segundo
    2.1 Subniveles.
    2.2 Otro mas

#. Sigue el orden.
#. Ordenada

termo (primera linea de texto)
    Definicion del termino.

    Seguimos con la definicion.

Bloques literales
-----------------
(DOBLE PUNTO) Despues de un texto normal podemos dejar un parrafo::

    def funcion (self):
        print (var)
        return None

(LINEA EN BLANCO REQUERIDA DESPUES DEL CODIGO)
El texto continua normal del bloque.

Bloque Doctest
--------------
No se requiere marca especial, solo un espacio
 >>> 1 + 1
 2

LINKS
-----
`Nombre pagina web <www.google.com>`_

 _`Daniel Castelao: www.google.com>`_

Tablas
------
Las tablas tienes que pintarlas tu:

+------------------------+------------+----------+----------+
| Header row, column 1   | Header 2   | Header 3 | Header 4 |
| (optional)             |            |          |          |
+========================+============+==========+==========+
| body row 1, column 1   | column 2   | column 3 | column 4 |
+------------------------+------------+----------+----------+
| body row 2             | ...        | ...      | bla bla  |
+------------------------+------------+----------+----------+

Otra forma de hacer tablas:

=====  =====  =======
A      B      A and B
=====  =====  =======
False  False  False
True   False  False
False  True   False
True   True   True
=====  =====  =======

Imagenes
--------

.. image:: _static/CD_icon.png
(Ruta relativa al directorio source)

Notas de pie
------------

.. rubric:: Notas
.. [#n1]:: Puedes encontrar mas informacion en tacata
