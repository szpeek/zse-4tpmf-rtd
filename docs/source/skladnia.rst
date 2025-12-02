=====================
 Sprawozdanie RtD
=====================
---------------------------------
 Nagłówki tekstowe (H1–H4)
---------------------------------

.. code-block:: rst

   Nagłówek poziomu 1
   ==================

.. code-block:: rst

   Nagłówek poziomu 2
   ------------------

.. code-block:: rst

   Nagłówek poziomu 3
   ~~~~~~~~~~~~~~~~~~

.. code-block:: rst

   Nagłówek poziomu 4
   ^^^^^^^^^^^^^^^^^^


---------------------------------
 Akapit tekstowy (treść)
---------------------------------

To jest zwykły akapit tekstu w reStructuredText.  
Może zawierać **pogrubienia**, *kursywę* itd.


-----------------------------------------------
 Akapit informacyjny: Note, Tip, etc.
-----------------------------------------------

.. note::

   To jest blok typu *Note*.

.. tip::

   To jest blok typu *Tip*.

.. warning::

   To jest blok typu *Warning*.


------------------------------------------------------
 Fragmenty kodu – inline i blokowe
------------------------------------------------------

Inline: ``print("Hello")``

Blok (domyślny, bez podświetlania):

::

   To jest blok kodu bez określonego języka.

Blok z podświetlaniem składni:

.. code-block:: python

   def hello():
       print("Hello, world!")


------------------------------------------------------
 Odnośniki – lokalne i zewnętrzne
------------------------------------------------------

Odnośnik lokalny (do innej strony RtD):

Zobacz :doc:`nazwa_strony`.

Odnośnik do sekcji:

Zobacz :ref:`etykieta_sekcji`.

Definicja etykiety sekcji:

.. _etykieta_sekcji:

Nagłówek sekcji
~~~~~~~~~~~~~~~~

Odnośnik zewnętrzny:

`OpenAI <https://www.openai.com>`_


----------------------------------------------
 Listy: wypunktowana, numerowana
----------------------------------------------

Lista wypunktowana:

- element 1
- element 2
  - element zagnieżdżony

Lista numerowana:

1. pierwszy
2. drugi
3. trzeci

Lista definicji:

Termin 1
   Definicja terminu 1.

Termin 2
   Definicja terminu 2.


---------------------------------
 Obraz z alt i podpisem
---------------------------------

.. figure:: image.jpg
   :alt: Przykładowy obrazek
   :width: 70%

   Podpis pod obrazem.


---------------------
 Tabela
---------------------

Prosta tabela gridowa:

+-----------+-----------+
| Kolumna 1 | Kolumna 2 |
+===========+===========+
| Wartość A | Wartość B |
+-----------+-----------+
| Wartość C | Wartość D |
+-----------+-----------+

Tabelka prostsza (simple table):

===========  ===========
Kolumna 1    Kolumna 2
===========  ===========
Wartość A     Wartość B
Wartość C     Wartość D
===========  ===========



