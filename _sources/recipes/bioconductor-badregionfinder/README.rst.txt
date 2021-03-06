:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-badregionfinder'
.. highlight: bash

bioconductor-badregionfinder
============================

.. conda:recipe:: bioconductor-badregionfinder
   :replaces_section_title:

   BadRegionFinder is a package for identifying regions with a bad\, acceptable and good coverage in sequence alignment data available as bam files. The whole genome may be considered as well as a set of target regions. Various visual and textual types of output are available.

   :homepage: https://bioconductor.org/packages/3.8/bioc/html/BadRegionFinder.html
   :license: LGPL-3
   :recipe: /`bioconductor-badregionfinder <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-badregionfinder>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-badregionfinder/meta.yaml>`_
   :links: biotools: :biotools:`badregionfinder`, doi: :doi:`10.1038/nmeth.3252`

   


.. conda:package:: bioconductor-badregionfinder

   |downloads_bioconductor-badregionfinder| |docker_bioconductor-badregionfinder|

   :versions: 1.10.0-0, 1.8.0-0, 1.6.0-0, 1.4.0-0
   
   :depends bioconductor-biomart: >=2.38.0,<2.39.0
   :depends bioconductor-genomicranges: >=1.34.0,<1.35.0
   :depends bioconductor-rsamtools: >=1.34.0,<1.35.0
   :depends bioconductor-s4vectors: >=0.20.0,<0.21.0
   :depends bioconductor-variantannotation: >=1.28.0,<1.29.0
   :depends r-base: >=3.5.1,<3.5.2.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-badregionfinder

   and update with::

      conda update bioconductor-badregionfinder

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-badregionfinder:<tag>

   (see `bioconductor-badregionfinder/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-badregionfinder| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-badregionfinder.svg?style=flat
   :alt:   (downloads)
.. |docker_bioconductor-badregionfinder| image:: https://quay.io/repository/biocontainers/bioconductor-badregionfinder/status
   :target: https://quay.io/repository/biocontainers/bioconductor-badregionfinder
.. _`bioconductor-badregionfinder/tags`: https://quay.io/repository/biocontainers/bioconductor-badregionfinder?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-badregionfinder/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-badregionfinder/README.html