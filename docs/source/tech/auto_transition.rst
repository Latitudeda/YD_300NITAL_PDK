auto_transition.py
====================

Define the transition between different waveguide type.

In **YD 300NITAL PDK**, a linear taper will be added between two same type of waveguides with different width. The ``SLOPE`` of taper is default to be 0.2.

In **YD 300NITAL PDK**, there is only one type of waveguide. Therefore, the transition between different waveguide types is not configured; however, users can add such transitions according to their specific needs for different waveguide types.

Users are allowed to define the taper and transition, and set ``DEFAULT`` to their own specific transition policy. Please see ``gpdk > components > transition`` for more examples.