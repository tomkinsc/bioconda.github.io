:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-metagxbreast'
.. highlight: bash

bioconductor-metagxbreast
=========================

.. conda:recipe:: bioconductor-metagxbreast
   :replaces_section_title:

   A collection of Breast Cancer Transcriptomic Datasets that are part of the MetaGxData package compendium.

   :homepage: https://bioconductor.org/packages/3.8/data/experiment/html/MetaGxBreast.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-metagxbreast <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-metagxbreast>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-metagxbreast/meta.yaml>`_

   


.. conda:package:: bioconductor-metagxbreast

   |downloads_bioconductor-metagxbreast| |docker_bioconductor-metagxbreast|

   :versions: 1.2.0-0
   
   :depends bioconductor-annotationhub: >=2.14.0,<2.15.0
   :depends bioconductor-biobase: >=2.42.0,<2.43.0
   :depends bioconductor-experimenthub: >=1.8.0,<1.9.0
   :depends bioconductor-impute: >=1.56.0,<1.57.0
   :depends r-base: >=3.5.1,<3.5.2.0a0
   :depends r-lattice: 
   :depends wget: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-metagxbreast

   and update with::

      conda update bioconductor-metagxbreast

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-metagxbreast:<tag>

   (see `bioconductor-metagxbreast/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-metagxbreast| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-metagxbreast.svg?style=flat
   :alt:   (downloads)
.. |docker_bioconductor-metagxbreast| image:: https://quay.io/repository/biocontainers/bioconductor-metagxbreast/status
   :target: https://quay.io/repository/biocontainers/bioconductor-metagxbreast
.. _`bioconductor-metagxbreast/tags`: https://quay.io/repository/biocontainers/bioconductor-metagxbreast?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-metagxbreast/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-metagxbreast/README.html