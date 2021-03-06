:github_url: hide

.. Generated automatically by doc/tools/makerst.py in Godot's source tree.
.. DO NOT EDIT THIS FILE, but the Vector2i.xml source instead.
.. The source is found in doc/classes or modules/<name>/doc_classes.

.. _class_Vector2i:

Vector2i
========

Vector used for 2D math using integer coordinates.

Description
-----------

2-element structure that can be used to represent positions in 2D space or any other pair of numeric values.

It uses integer coordinates.

Tutorials
---------

- :doc:`../tutorials/math/index`

Methods
-------

+---------------------------------+--------------------------------------------------------------------------------------------------------------+
| :ref:`Vector2i<class_Vector2i>` | :ref:`Vector2i<class_Vector2i_method_Vector2i>` **(** :ref:`int<class_int>` x, :ref:`int<class_int>` y **)** |
+---------------------------------+--------------------------------------------------------------------------------------------------------------+
| :ref:`Vector2i<class_Vector2i>` | :ref:`Vector2i<class_Vector2i_method_Vector2i>` **(** :ref:`Vector2<class_Vector2>` from **)**               |
+---------------------------------+--------------------------------------------------------------------------------------------------------------+

Constants
---------

.. _class_Vector2i_constant_AXIS_X:

.. _class_Vector2i_constant_AXIS_Y:

.. _class_Vector2i_constant_ZERO:

.. _class_Vector2i_constant_ONE:

.. _class_Vector2i_constant_LEFT:

.. _class_Vector2i_constant_RIGHT:

.. _class_Vector2i_constant_UP:

.. _class_Vector2i_constant_DOWN:

- **AXIS_X** = **0** --- Enumerated value for the X axis.

- **AXIS_Y** = **1** --- Enumerated value for the Y axis.

- **ZERO** = **Vector2i( 0, 0 )** --- Zero vector.

- **ONE** = **Vector2i( 1, 1 )** --- One vector.

- **LEFT** = **Vector2i( -1, 0 )** --- Left unit vector.

- **RIGHT** = **Vector2i( 1, 0 )** --- Right unit vector.

- **UP** = **Vector2i( 0, -1 )** --- Up unit vector.

- **DOWN** = **Vector2i( 0, 1 )** --- Down unit vector.

Method Descriptions
-------------------

.. _class_Vector2i_method_Vector2i:

- :ref:`Vector2i<class_Vector2i>` **Vector2i** **(** :ref:`int<class_int>` x, :ref:`int<class_int>` y **)**

Constructs a new ``Vector2i`` from the given ``x`` and ``y``.

----

- :ref:`Vector2i<class_Vector2i>` **Vector2i** **(** :ref:`Vector2<class_Vector2>` from **)**

Constructs a new ``Vector2i`` from :ref:`Vector2<class_Vector2>`. The floating point coordinates will be truncated.

