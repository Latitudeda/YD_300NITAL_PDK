auto_vias.py
====================

Define the vias between different metal line type.

In **YD 300NITAL PDK**, there is only one metal layer. When metals with different width are connected, a linear taper is used for transition.

Users are allowed to change slope of the linear taper by their own specific requirements. Please see ``technology > auto_vias.py`` to modifiy the default slope.