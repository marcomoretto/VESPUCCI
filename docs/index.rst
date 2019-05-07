.. VESPUCCI documentation master file, created by
   sphinx-quickstart on Tue May  7 11:32:26 2019.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

.. |email| image:: _static/email.png

Welcome to VESPUCCI's documentation!
====================================

VESPUCCI is a `COMMAND>_ <https://command.readthedocs.io>`_ technology-based database for exploring and analyzing a comprehensive *Vitis vinifera* specific cross-platform expression compendium. This compendium was carefully constructed by collecting, homogenizing and formally annotating publicly available microarray and RNA-seq experiments from `Gene Expression Omnibus (GEO) <https://www.ncbi.nlm.nih.gov/geo/>`_, `Sequence Reads Archive (SRA) <https://www.ncbi.nlm.nih.gov/sra>`_ `and ArrayExpress <https://www.ebi.ac.uk/arrayexpress/>`_.

VESPUCCI's major features include: 

1. Access to gene expression compendium that combine information from different platforms and experiments.
2. Integration of information from main curated databases allowing the user to interactively browse and query the compendia for specific genes, pathways, protein domains, and more.
3. An extensive formal sample annotation, allowing the user to interactively browse and query the compendia not only for specific arrays, samples, or experiments, but also for specific experimental conditions and biological processes.
4. A suite of flexible yet intuitive tools to explore, analyze and visualize the expression data in the compendium.
5. Powerful programmatic access to the database via a `GraphQL <https://graphql.org/>`_ web service. We also provide an API to connect to and query the VESPUCCI database directly from within `Python <https://command.readthedocs.io>`_ and R.

How to cite
-----------

If you use VESPUCCI and find it useful please cite:

Moretto, M. et al. (2016). *VESPUCCI: exploring patterns of gene expression in grapevine.* Frontiers in plant science, 7, 633. `doi 10.3389/fpls.2016.00633 <https://www.frontiersin.org/articles/10.3389/fpls.2016.00633/full>`_


.. toctree::
   :maxdepth: 2
   :caption: Table of Contents

   query_vespucci
   use_cases
   

Author
======

To send me an e-mail about anything else related to VESPUCCI write to |email|

License
=======

The project is licensed under the `GPLv3 license <https://www.gnu.org/licenses/gpl-3.0.html>`_.