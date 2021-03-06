:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-flowmatch'
.. highlight: bash

bioconductor-flowmatch
======================

.. conda:recipe:: bioconductor-flowmatch
   :replaces_section_title:

   Matching cell populations and building meta\-clusters and templates from a collection of FC samples.

   :homepage: https://bioconductor.org/packages/3.8/bioc/html/flowMatch.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-flowmatch <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-flowmatch>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-flowmatch/meta.yaml>`_
   :links: biotools: :biotools:`flowmatch`, doi: :doi:`10.1038/nmeth.3252`

   


.. conda:package:: bioconductor-flowmatch

   |downloads_bioconductor-flowmatch| |docker_bioconductor-flowmatch|

   :versions: 1.18.0-0, 1.16.0-0, 1.14.0-0
   
   :depends bioconductor-biobase: >=2.42.0,<2.43.0
   :depends bioconductor-flowcore: >=1.48.0,<1.49.0
   :depends libgcc-ng: >=7.3.0
   :depends libstdcxx-ng: >=7.3.0
   :depends r-base: >=3.5.1,<3.5.2.0a0
   :depends r-rcpp: >=0.11.0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-flowmatch

   and update with::

      conda update bioconductor-flowmatch

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-flowmatch:<tag>

   (see `bioconductor-flowmatch/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-flowmatch| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-flowmatch.svg?style=flat
   :alt:   (downloads)
.. |docker_bioconductor-flowmatch| image:: https://quay.io/repository/biocontainers/bioconductor-flowmatch/status
   :target: https://quay.io/repository/biocontainers/bioconductor-flowmatch
.. _`bioconductor-flowmatch/tags`: https://quay.io/repository/biocontainers/bioconductor-flowmatch?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-flowmatch/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-flowmatch/README.html