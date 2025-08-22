PDK structure
======================

Process Design Kit (PDK) is a tool for designated users to generate circuit layouts based on **YD 300NITAL** design rules and technology settings.

``YF_300NITAL_V1p5_Latitudeda`` package includes three subfolders: ``components``, ``examples``, and ``technology``.

* ``components``

    * Fixed cells: All fixed cells, including ``DirectionalCoupler_CBTE_YDME_BB``, ``EdgeCoupler_CBTE_YDME_BB``, ``MicroRing_CBTE_YDME_BB``, etc, are named and designed by **YDME** and cannot be changed.

    * Parametrized cells (PCells): Designed by **Latitudeda**, including ``Bend``, ``Straight``, ``Taper``, etc. Please see ``gpdk > components`` for more designed components by **Latitudeda**.

* ``examples``

    * ``tech_test.py`` : Tests that waveguide types, metal wire types, auto routing, and auto link function works normally under the PDK setting. Please see ``gpdk > examples`` for more circuit examples.

* ``technology``

    * Store the technology setting which matched the **YD 300NITAL** design rules. We recommend users not to change the settings in technology folder.

    * See chapter ``Technology setting`` for more specific definition.

* ``YD_300NITAL_V1p5_Latitudeda.lyp``

    * This file allows layout tools e.g. Klayout to recognize the layer information when displaying gds file to the layout tool.

    .. image:: ../images/lyp.png
