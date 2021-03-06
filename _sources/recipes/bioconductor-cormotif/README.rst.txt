:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-cormotif'
.. highlight: bash

bioconductor-cormotif
=====================

.. conda:recipe:: bioconductor-cormotif
   :replaces_section_title:

   It fits correlation motif model to multiple studies to detect study specific differential expression patterns.

   :homepage: https://bioconductor.org/packages/3.8/bioc/html/Cormotif.html
   :license: GPL-2
   :recipe: /`bioconductor-cormotif <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-cormotif>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-cormotif/meta.yaml>`_
   :links: biotools: :biotools:`cormotif`

   


.. conda:package:: bioconductor-cormotif

   |downloads_bioconductor-cormotif| |docker_bioconductor-cormotif|

   :versions: 1.28.0-0, 1.26.0-0, 1.24.0-0
   
   :depends bioconductor-affy: >=1.60.0,<1.61.0
   :depends bioconductor-limma: >=3.38.0,<3.39.0
   :depends r-base: >=3.5.1,<3.5.2.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-cormotif

   and update with::

      conda update bioconductor-cormotif

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-cormotif:<tag>

   (see `bioconductor-cormotif/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-cormotif| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-cormotif.svg?style=flat
   :alt:   (downloads)
.. |docker_bioconductor-cormotif| image:: https://quay.io/repository/biocontainers/bioconductor-cormotif/status
   :target: https://quay.io/repository/biocontainers/bioconductor-cormotif
.. _`bioconductor-cormotif/tags`: https://quay.io/repository/biocontainers/bioconductor-cormotif?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-cormotif/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-cormotif/README.html