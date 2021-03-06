:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-otubase'
.. highlight: bash

bioconductor-otubase
====================

.. conda:recipe:: bioconductor-otubase
   :replaces_section_title:

   Provides a platform for Operational Taxonomic Unit based analysis

   :homepage: https://bioconductor.org/packages/3.8/bioc/html/OTUbase.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-otubase <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-otubase>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-otubase/meta.yaml>`_
   :links: biotools: :biotools:`otubase`, doi: :doi:`10.1093/bioinformatics/btr196`

   


.. conda:package:: bioconductor-otubase

   |downloads_bioconductor-otubase| |docker_bioconductor-otubase|

   :versions: 1.32.0-0, 1.30.0-0, 1.28.0-0, 1.26.0-0
   
   :depends bioconductor-biobase: >=2.42.0,<2.43.0
   :depends bioconductor-biostrings: >=2.50.0,<2.51.0
   :depends bioconductor-iranges: >=2.16.0,<2.17.0
   :depends bioconductor-s4vectors: >=0.20.0,<0.21.0
   :depends bioconductor-shortread: >=1.40.0,<1.41.0
   :depends r-base: >=3.5.1,<3.5.2.0a0
   :depends r-vegan: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-otubase

   and update with::

      conda update bioconductor-otubase

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-otubase:<tag>

   (see `bioconductor-otubase/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-otubase| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-otubase.svg?style=flat
   :alt:   (downloads)
.. |docker_bioconductor-otubase| image:: https://quay.io/repository/biocontainers/bioconductor-otubase/status
   :target: https://quay.io/repository/biocontainers/bioconductor-otubase
.. _`bioconductor-otubase/tags`: https://quay.io/repository/biocontainers/bioconductor-otubase?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-otubase/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-otubase/README.html