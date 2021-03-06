:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-yamss'
.. highlight: bash

bioconductor-yamss
==================

.. conda:recipe:: bioconductor-yamss
   :replaces_section_title:

   Tools to analyze and visualize high\-throughput metabolomics data aquired using chromatography\-mass spectrometry. These tools preprocess data in a way that enables reliable and powerful differential analysis.

   :homepage: https://bioconductor.org/packages/3.8/bioc/html/yamss.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-yamss <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-yamss>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-yamss/meta.yaml>`_
   :links: biotools: :biotools:`yamss`

   


.. conda:package:: bioconductor-yamss

   |downloads_bioconductor-yamss| |docker_bioconductor-yamss|

   :versions: 1.8.1-0, 1.4.0-0
   
   :depends bioconductor-biocgenerics: >=0.28.0,<0.29.0
   :depends bioconductor-ebimage: >=4.24.0,<4.25.0
   :depends bioconductor-iranges: >=2.16.0,<2.17.0
   :depends bioconductor-limma: >=3.38.0,<3.39.0
   :depends bioconductor-mzr: >=2.16.0,<2.17.0
   :depends bioconductor-s4vectors: >=0.20.0,<0.21.0
   :depends bioconductor-summarizedexperiment: >=1.12.0,<1.13.0
   :depends r-base: >=3.5.1,<3.5.2.0a0
   :depends r-data.table: 
   :depends r-matrix: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-yamss

   and update with::

      conda update bioconductor-yamss

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-yamss:<tag>

   (see `bioconductor-yamss/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-yamss| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-yamss.svg?style=flat
   :alt:   (downloads)
.. |docker_bioconductor-yamss| image:: https://quay.io/repository/biocontainers/bioconductor-yamss/status
   :target: https://quay.io/repository/biocontainers/bioconductor-yamss
.. _`bioconductor-yamss/tags`: https://quay.io/repository/biocontainers/bioconductor-yamss?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-yamss/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-yamss/README.html