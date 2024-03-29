Query VESPUCCI
==============

VESPUCCI is accessible via the `COMPASS <https://compass-.readthedocs.io>`_ `GraphQL <https://graphql.org/>`_ interface that has been specifically developed to facilitate data retrivial and analysis of gene expression compendia built with the `COMMAND>_ <https://command.readthedocs.io>`_ technology. 
You have four options to query VESPUCCI:

 1. use the GraphQL endpoint directly, `COMPASS <https://compass-.readthedocs.io>`_

 2. use the Python package `pyCOMPASS <https://pycompass.readthedocs.io>`_

 3. use the R package `rCOMPASS <https://onertipaday.github.io/rcompass/>`_

We recomend to use either option 2 or 3 unless you need to use the GraphQL endpoint specifically. Both the Python and R packages provide the same options as the GraphQL endpoint but with all the expressiveness of a higher order programming language. Option 4 is not meant for data analysis but to showcase how to create tools on top of pyCOMPASS, rCOMPASS or COMPASS directly.

Use the GraphQL endpoint
------------------------
*GraphQL is an open-source data query and manipulation language for APIs, and a runtime for fulfilling queries with existing data*. The GraphQL interface to access VESPUCCI is `COMPASS <https://compass-.readthedocs.io>`_. The GraphQL endpoint is available at http://vespucci.fmach.it/compass.

Use Python package pyCOMPASS
----------------------------
`pyCOMPASS <https://pycompass.readthedocs.io>`_ is the Python interface for the COMPASS GraphQL interface. It is the preferred way to access VESPUCCI for data analysis purpose since it provides with higher level functionalities. You can install pyCOMPASS via PIP:

.. code-block:: python

    pip install pycompass

Use the R package rCOMPASS
--------------------------
`rCOMPASS <https://onertipaday.github.io/rcompass/>`_ is the R interface for the COMPASS GraphQL interface. It is the preferred way to access VESPUCCI for data analysis purpose since it provides with higher level functionalities. You can install rCOMPASS from github:

.. code-block:: R

    devtools::install_github("onertipaday/rcompass")

