Float List
==========

Description
-----------

This node is used to create an arbitrary list of floats. A new float can be added with the *New Input* button. A new float can also be added by plugging it into the transparent socket.

.. image:: images/float_list_node.png
   :width: 160pt

Inputs
------

- **Float** - A float at the index 0.
- **Float** - A float at the index 1.
- **Float** - ...

Outputs
-------

- **Float list** - A list that contains all the input floats.

Advanced Node Settings
----------------------

- **Change type** - Changes the type of the float list to another list type.
- **Hide Inputs** - Hides all the inputs in the node.
- **Remove Unlinked Inputs** - Removes all the inputs that are not connected to another node.

Caution
-------

A warning will pop up when you use the *Remove Unlinked Inputs* button in the node, while if you used the the *Remove Unlinked Inputs* button in the *Advanced Node Settings* the inputs will be removed without a warning.

Examples of Usage
-----------------

.. image:: gifs/float_list_node_example.gif
